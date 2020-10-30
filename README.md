# SudokuSolverPython
This Project will Solve the given sudoku board by Back-Tracking.

Sudoku solver with python, explain how we are going to go about solving the problem and discuss the algorithm known as backtracking. 
Backtracking is simply reverting back to the previous step or solution as soon as we determine that our current solution cannot be continued into a complete one. We will use this principle of backtracking to implement the following algorithm.

Algorithm

Starting with an incomplete board:

    1.Find some empty space
    2.Attempt to place the digits 1-9 in that space
    3.Check if that digit is valid in the current spot based on the current board
    4.1. If the digit is valid, recursively attempt to fill the board using steps 1-3.
    4.2. If it is not valid, reset the square you just filled and go back to the previous step.
    5.Once the board is full by the definition of this algorithm we have found a solution.

We will finish about half of the algorithm in part 1. 

for reference please visit the following blogs,

1.https://towardsdatascience.com/solve-sudokus-automatically-4032b2203b64

2.https://medium.com/datadriveninvestor/solving-sudoku-in-seconds-or-less-with-python-1c21f10117d6

(for better understanding)
