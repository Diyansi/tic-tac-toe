# Tic-Tac-Toe Game

This is a Tic-Tac-Toe game implementation in C where the computer plays against the human player. The game uses the Minimax algorithm to determine the best move for the computer.

## Features
- **Player vs Computer**: The game allows a human player to play against the computer.
- **Minimax Algorithm**: The computer uses the Minimax algorithm to choose the optimal move.
- **Board Display**: The board is displayed after every move, showing the current state of the game.
- **Instructions**: The game provides clear instructions for the human player on how to play.

## Game Rules
- The game is played on a 3x3 grid.
- The human player plays with 'X' and the computer plays with 'O'.
- Players take turns making moves, and the first player to get 3 of their symbols in a row (horizontally, vertically, or diagonally) wins.
- The game ends when either the human or the computer wins, or when the board is full (draw).

## Functions
- `isMovesLeft(board)`: Checks if there are any moves left on the board.
- `evaluate(board)`: Evaluates the current board state and returns a score based on the result (win/lose/draw).
- `minimax(board, depth, isMax)`: Implements the Minimax algorithm to compute the best move for the computer.
- `findBestMove(board)`: Finds the best move for the computer based on the Minimax evaluation.
- `showBoard(board)`: Displays the current state of the board.
- `showInstructions()`: Displays the instructions for the human player.
- `initialise(board, moves)`: Initializes the board and randomizes possible moves.
- `declareWinner(whoseTurn)`: Declares the winner of the game.
- `gameOver(board)`: Checks if the game has ended.
  
## How to Play
1. The game starts with an empty 3x3 board.
2. The human player is asked to input a number between 1-9, corresponding to the empty cells of the board.
3. The computer uses the Minimax algorithm to choose its move and updates the board.
4. The game alternates between the human and the computer until one player wins or the game ends in a draw.

## Requirements
- C Compiler (e.g., GCC)
- Basic understanding of C programming

## created by
Diyansi Chaudhary
