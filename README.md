# AI Tic Tac Toe

This repository showcases an implementation of a Tic Tac Toe game against an AI opponent using the minimax algorithm in Python.

## How to Play

1. Run the script.
2. Enter your move by specifying the row and column (1 to 3) when prompted.
3. The AI opponent, utilizing the minimax algorithm, will make its move.
4. The game continues until there is a winner, a draw, or you choose to exit.

## Code Overview

The game is structured as follows:

- The game board is represented as a 3x3 numpy array.
- The `print_board(board)` function prints the current state of the board.
- The `check_win(board, player)` function checks for a win based on rows, columns, and diagonals.
- The minimax algorithm is implemented in the `minimax(board, depth, is_maximizing)` function, which determines the best move for the AI.
- The AI's move is calculated using the `ai_move(board)` function.

The main game loop allows players to make moves, and the game state is continuously updated until a winner is determined or a draw occurs.

Feel free to explore and challenge the AI in this Tic Tac Toe showdown!

# Author
Kartik Jindal

Contact: kartikjindal2003@example.com
