# Tic Tac Toe

A simple implementation of the classic Tic-Tac-Toe game, where two players take turns marking `X` or `O` on a 3x3 grid. The goal is to get three of your marks in a row—horizontally, vertically, or diagonally.

## Features
- **Human vs Human**: Two players can play against each other.
- **AI Player**: The AI uses the Minimax algorithm to make optimal moves.
- **Game State Management**: Keeps track of the current state of the board, whose turn it is, and checks if the game has been won or drawn.

## Game Rules
1. The game is played on a 3x3 grid.
2. Players take turns to place their mark (`X` or `O`) on an empty space.
3. The first player to get 3 marks in a row (horizontally, vertically, or diagonally) wins.
4. If all 9 spaces are filled and no player has 3 marks in a row, the game ends in a draw.

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/tictactoe.git

Make sure you have Python 3 installed.

Run the game by executing the runner.py script:

python3 runner.py
