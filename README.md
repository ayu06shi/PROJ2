# PROJ2
 Sudoku Solver

This is a Sudoku Solver code. It uses the basics of c++ programming and its simple algorithm.
It has 7 functions: 

isPresentInRow(), isPresentInCol() and isPresentInBox() are used to check whether the particular number is present in the row, column and box respectively by taking inputs of row no, column no. and boxStartRow and boxStartColumn and the number to be inputted. If these return false, only then the number is inserted in that position.

sudokuGrid() prints the solved sudoku grid on the console.

solveSudoku() is an important recursive function that calls findEmptyPlace() and isValidPlace() to check for empty and valid place for the valid numbers. These functions further call isPresentInRow(), isPresentInCol() and isPresentInBox() to find valid locations.
