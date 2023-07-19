# Connect Four Game
LIVE: https://esmanerdem.github.io/oopConnectFour/

## Overview

Connect Four is a classic two-player game where players take turns dropping colored discs from the top into a grid. The objective of the game is to connect four of your own discs in a row, either horizontally, vertically, or diagonally, before your opponent does.

## How to Play

1. To start the game, enter the preferred colors for Player 1 and Player 2 in the input fields provided.

2. Click the "Start Game!" button to begin.

3. The game board will be displayed with an empty grid.

4. Players will take turns dropping their colored discs into the columns by clicking on the top row of the desired column.

5. The disc will fall to the lowest available slot in the selected column.

6. The game will continue until one of the players successfully connects four of their colored discs in a row, or if the game board is fully filled without a winner.

7. If a player wins or the game ends in a tie, a message will be displayed announcing the result.

8. To restart the game, click the "Restart" button.

## JavaScript Code

The JavaScript code provided in `connect4.js` handles the game logic and DOM manipulation. It defines a `Game` class, which represents the Connect Four game. The class constructor takes four arguments: `height`, `width`, `p1`, and `p2`, representing the height and width of the game board, and the colors chosen by Player 1 and Player 2, respectively.

The `Game` class contains methods for creating the game board, updating the HTML table, handling player turns and moves, checking for a win condition, and displaying messages for the game result.

The game board is represented as a 2D array, and the pieces are displayed as colored circles within the cells of the HTML table. The game uses event listeners to handle player interactions and updates the board accordingly.

To start the game, enter the colors for both players, click "Start Game!", and take turns dropping your colored discs until one player wins or the game ends in a tie.

## How to Clone

To clone this repository and run the Connect Four game locally on your machine, follow these steps:

1. Open your terminal or command prompt.

2. Change the current working directory to the location where you want to clone the repository.

3. Run the following command to clone the repository:

https://github.com/EsmaNErdem/oopConnectFour.git

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or improvements, please feel free to submit a pull request.


