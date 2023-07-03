# Tic-Tac-Toe Game

This is a simple implementation of the Tic-Tac-Toe game using Java programming language. The game allows two players to take turns and compete to win by forming a line of their respective marks (X or O) on a 3x3 grid.

## How to Play

1. The game starts with an empty 3x3 grid.
2. Two players take turns, one playing as "X" and the other as "O".
3. On your turn, enter the row and column numbers to place your mark on the grid.
4. The game continues until a player wins or there is a draw.
5. A player wins by forming a line of their marks horizontally, vertically, or diagonally.
6. If all the cells on the grid are filled and no player has won, the game is a draw.

## Getting Started

To run the Tic-Tac-Toe game, follow these steps:

1. Make sure you have Java Development Kit (JDK) installed on your system.
2. Download the source code files for the game (TicTacToe.java).
3. Open a command prompt or terminal and navigate to the directory where the source code is saved.
4. Compile the source code by running the following command: `javac TicTacToe.java`
5. Run the game by executing the compiled class file: `java TicTacToe`
6. The game will start, and you can follow the on-screen instructions to play.

## Implementation Details

The game is implemented using Java and follows a simple command-line interface. It utilizes a 2D array to represent the game board. Each player's move is validated to ensure it falls within the valid range and on an empty cell. The game checks for a winning condition after each move and also determines if the game ends in a draw.

The `TicTacToe` class contains methods to initialize the board, print the current state of the board, check for a win or draw, and handle player moves. The main method initializes an instance of the `TicTacToe` class and starts the game loop.

Please note that this implementation does not include advanced features such as AI opponents or graphical user interface (GUI). It serves as a basic introduction to the game logic, and you can further enhance it to add additional functionality based on your requirements.

Enjoy playing Tic-Tac-Toe!
