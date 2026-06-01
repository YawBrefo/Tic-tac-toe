[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

# Tic-Tac-Toe game

This is a Python implementation of Tic-Tac-Toe board game that checks a completed board for a winner. It is designed to work with any square board size — not just the standard 3×3 matrix board.

Feedback welcome: bdwamena@aimsammi.org

## How It Works:

`tic_tac_toe(board)` takes a 2-Dimensional list representing a filled board and checks four winning conditions:

| Condition | Description |
|---|---|
| Row | All cells in any row match |
| Column | All cells in any column match |
| Forward diagonal | Cells along the top-left → bottom-right diagonal match |
| Back diagonal | Cells along the top-right → bottom-left diagonal match |

If a winning alignment is found, it prints the winner (`x` or `o`), the alignment type, and "Game Over!!". If no alignment is found, it prints `NO WINNER!!`.

## Usage

```python
Game_board = [['x', 'x', 'o'],
              ['x', 'o', 'o'],
              ['o', 'x', 'x']]

tic_tac_toe(Game_board)
# o have won! Game Over!! from the back diagonal allignment
```

The board can be any size — pass an n×n list and the function adapts automatically.

## Dependencies

Only Python, no external libraries required.

## Planned Improvements

- Interactive player input
- GUI for a better visual experience

