# sudoku-solver
Sudoku Solver in python
This code uses a backtracking algorithm to solve the sudoku. 
The function solve_sudoku takes in a 2D list representing the sudoku board,
and solves it by iterating through each empty cell, trying every possible number from 1 to 9,
and checking if the number is valid in that cell.
If the number is valid, it assigns that number to the cell and continues solving the rest of the board.
If it reaches a point where it can't find a valid number for a cell, it backtracks to the previous cell and tries a different number.
Once the function solves the entire board, it returns True, indicating that the board is solved.
The helper functions is_valid, find_empty are used to check if the number is valid in the given position and to find the next empty cell respectively.
