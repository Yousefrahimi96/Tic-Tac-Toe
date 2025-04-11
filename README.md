# Tic-Tac-Toe Game

This is a simple implementation of the classic **Tic-Tac-Toe** game written in Python. The game allows two players to compete on a 3x3 grid, taking turns to place their symbols ('X' or 'O') until one wins or the game ends in a draw. The first player is chosen randomly at the start of each game.

## Features

- Random selection of the starting player ('X' or 'O').
- Validation of player moves with error handling for invalid inputs.
- Automatic detection of win conditions after each move.
- Detection of a draw when the board is full with no winner.
- Simple and clean console-based interface.

## How to Play

1. **Run the game**: Execute the Python script to launch the game.
2. **Enter your move**: When prompted, input a number between 1 and 9 corresponding to a cell on the board:<br />
[1, 2, 3]<br />
[4, 5, 6]<br />
[7, 8, 9]
3. **Game progression**: Players alternate turns, placing their symbol in an empty cell.
4. **Win or Draw**: The game ends when a player aligns three symbols (horizontally, vertically, or diagonally) or when the board is full (resulting in a draw).

## Installation

1. **Clone the repository**:
```bash
git clone https://github.com/yousefrahimi96/tictactoe.git
```
2. **Navigate to the project directory**:
```bash
cd tictactoe
```
3. **Run the game**:
```bash
python3 tictactoe.py
```