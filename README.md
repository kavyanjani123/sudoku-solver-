SUDOKU SOLVER 

The Sudoku Solver project aims to develop a C++ program that can solve Sudoku puzzles using the backtracking algorithm. The backtracking approach will systematically search for a solution by exploring possible number placements in the grid and backtracking when a conflict arises. This project will enhance understanding of recursive algorithms and constraint satisfaction problems.

Objectives:

Input Handling: Create mechanisms to input Sudoku puzzles via console or file.
Sudoku Validation: Implement functions to check the validity of the Sudoku grid.
Backtracking Algorithm: Develop a backtracking algorithm to solve the puzzle.
Output: Display the solved Sudoku grid.

Features:

User Input: Allow users to input Sudoku puzzles through a console interface or by reading from a file.
Grid Display: Display the initial and solved Sudoku grids in a clear, readable format.
Validation: Ensure that the input Sudoku puzzle adheres to standard Sudoku rules.
Backtracking Algorithm: Implement a recursive backtracking algorithm that:
Iteratively tries numbers 1 through 9 in empty cells.
Checks for conflicts in the current row, column, and 3x3 subgrid.
Backtracks when a conflict is detected, undoing the last placement and trying the next possible number.
Efficiency: Optimize the algorithm to handle complex puzzles efficiently.
Error Handling: Provide informative error messages for invalid inputs or unsolvable puzzles.

Backtracking Algorithm:

Find an empty cell in the grid.
For numbers 1 to 9, do the following:
Place the number in the cell if it doesn't violate Sudoku rules.
Recursively attempt to solve the rest of the grid.
If the grid is solved, return true.
If placing the number leads to a conflict, remove the number and try the next one.
If no numbers work, return false to trigger backtracking
