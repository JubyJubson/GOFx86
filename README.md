# GOFx86
Game of life in Assembly x86

The GOF.txt file contains the code for the Game of Life.

I used Linux to run the code. For the input, you need to provide the following, in this exact order:

1). An integer representing the number of rows in the matrix where the "game" takes place.
2). An integer representing the number of columns in the matrix where the "game" takes place.
3). An integer 𝑁 representing the number of live cells you want to create and place in the matrix by specifying their coordinates as indexes (Example: 0,0 is the top-left cell of the matrix. Note that all cells not specified as alive are dead, represented by 0, while live cells are represented by 1).
4). 2×𝑁 integers that represent the coordinates of the live cells, given one by one. For example: 1\n 1 means you want to set the cell located at row 1, column 1 to be alive.
5). A final integer representing the number of steps after which you want to see the evolution of your pattern.


For those unfamiliar with the rules of the Game of Life, here is a short explanation:

The Game of Life, created by mathematician John Conway, is a zero-player game that simulates cellular automata. It takes place on a grid of cells, where each cell can be either alive (1) or dead (0). The state of the grid evolves in discrete steps based on the following rules:

Survival: A live cell with 2 or 3 live neighbors stays alive.
Death: A live cell with fewer than 2 live neighbors dies (underpopulation), and a live cell with more than 3 live neighbors dies (overpopulation).
Birth: A dead cell with exactly 3 live neighbors becomes alive (reproduction).

Here is a link if you want to experiment and see the fascinating patterns that can be created using these rules: https://playgameoflife.com/.
