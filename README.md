Patika Week 3

Minesweeper Game

A MineSweeper class is being created where methods will be defined.

We are creating a method in which the user selects the area they want to play by calling a constructor method, with the condition that the size of the entered area should not be smaller than 2x2.

We call the isValidDimensions method to determine the game area in the constructor method

We randomly place mines on 1/4 of the selected area on the game board.

We ask the user to select a point.

If there is a mine at the point chosen by the user, they lose the game.

If there is no mine at the point chosen by the user, we check the points around it and print the total number of mines in those points on the board.

We define a boolean matrix for the points chosen by the user, and if the user selects the same point again, we print an error message on the screen indicating that they have selected that point before.

If the user selects all points without mines, they win the game.
