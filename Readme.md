# N-Queens Visualizer
This is a web-based visualizer for the N-Queens Problem. The N-Queens problem is a classic computer science puzzle where the goal is to place N queens on an N×N chessboard in such a way that no two queens can attack each other. This means no two queens can share the same row, column, or diagonal.

The visualizer allows users to specify the size of the chessboard and view all possible solutions for that size.


## Features
- Allows input for N, the size of the chessboard.
- Generates and visualizes all valid solutions for placing N queens.
- Displays the chessboard with alternating colors for cells.
- Uses images of queens to visually indicate their placement on the board.

## How the N-Queens Problem is Solved
This visualizer uses a backtracking algorithm to solve the N-Queens problem. Backtracking is a recursive approach that tries placing queens one by one and backtracks if it encounters an invalid placement.

    1. The board is filled row by row.
    2. For each row, the algorithm tries to place a queen in each column.
    3. If a valid placement is found, it moves to the next row.
    4. If no valid placement is found in a row, it backtracks to the previous row and tries the next possible placement.
Once a valid placement for all queens is found, the solution is stored and displayed.

## Screenshots
