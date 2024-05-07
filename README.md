# Tic-Tac-Toe-Python

A simple implementation of a Tic-Tac-Toe game in Python with object-oriented programming.

## Game Description
This project is a terminal-based Tic-Tac-Toe game where two players take turns to place their pieces on a 3x3 board. The objective is to align three pieces vertically, horizontally, or diagonally. The first player to achieve this wins the game. If all spaces are filled without a winner, the game is declared a tie.

## Features
- Two-player mode: `x` vs `o`
- Input validation to prevent placing pieces in an already occupied space or out-of-bounds index
- Displays the game board after each turn
- Detects winning and tie conditions
- Allows for restarting the game after it ends

## How to Play
1. The game will prompt the first player (`x`) to choose a row and column index for their move.
2. The second player (`o`) will then be prompted to do the same.
3. Players alternate turns until:
   - A player wins by aligning three pieces vertically, horizontally, or diagonally.
   - The board is full, resulting in a tie.
4. The game will then ask if you want to play again.

## How to Run the Game
1. Ensure you have Python 3 installed on your system.
2. Clone or download this repository to your local machine.
3. Navigate to the directory where `tic_tac_toe.py` is located.
4. Run the game using the following command:

```bash
python3 tic_tac_toe.py
