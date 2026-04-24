[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

# Tic-Tac-Toe

A Python implementation of Tic-Tac-Toe that checks a completed board for a winner. It is designed to work with any square board size — not just the standard 3×3 matrix.

Feedback welcome: bdwamena@aimsammi.org

## How It Works

`tic_tac_toe(board)` takes a 2D list representing a filled board and checks four winning conditions:

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

None — pure Python, no external libraries required.

## Planned Improvements

- Interactive player input
- GUI for a better visual experience

