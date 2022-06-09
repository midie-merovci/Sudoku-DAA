# Sudoku-DAA

This project implements the game of Sudoku. It focuses on implementing algorithms that:
Generate sudoku initial values
Solve sudoku with the given values
Each time the program is run, one sudoku matrix with some initial values is generated, and then the solveSudoku function takes this matrix as a parameter, and solves it, giving a totally solved sudoku matrix. 
As a last step we remove K values from solved sudoku matrix, and display them to the user. User is able to play the game and the program can control every move that user plays, comparing it with the already solved sudoku we have. UI of the program is web based, users can play the game using browser, .

Technologies:
To develop the logic behind sudoku we used pure javascript, since it’s very compatible with web based programs, and for the UI we used react.


How is Sudoku game played?
Sudoku game is basically a 9x9 matrix that requires from the player to be filled in a specific way. Usually when we see a sudoku it has some boxes filled with numbers from 1 to 9, based on them we can continue to fill other boxes. For a number to be valid in a box there are some rules that should be applied. The number to be inserted must:
Be unique in the row
Be unique in the column
Be unique in the 3x3 box
Sometimes there are just a few initial values in the sudoku matrix, which makes it a difficult to solve sudoku. In this case it is very possible that the number you want to insert, fills all those 3 rules, yet that is not the correct value to put in that box. Sudoku is solved using the players’ skills to predict future steps of the game, seeing if the progress is being towards solving the sudoku, or making it unsolvable.
