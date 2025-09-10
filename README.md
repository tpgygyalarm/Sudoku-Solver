# Sudoku Solver

This project implements a Sudoku solver using a backtracking algorithm in Python.

## Features

- Solves standard 9x9 Sudoku puzzles
- Uses a simple and readable backtracking algorithm
- Hardcoded input grid for demonstration
- Prints the initial and solved Sudoku grid

## Usage

1. Save the script as `sudoku_solver.py`.
2. Run the script with Python:

   ```bash
   python sudoku_solver.py
   ```

3. You will see the initial puzzle and the solved solution printed in the terminal.

## Example

```
Initial Sudoku grid:
5 1 7 6 . . . 3 4
2 8 9 . . 4 . . .
3 4 6 2 . 5 . 9 .
6 . 2 . . . . 1 .
. 3 8 . . 6 . 4 7
. . . . . . . . .
. 9 . . . . . 7 8
7 . 3 4 . . 5 6 .
. . . . . . . . .
```

After solving:

```
Solved Sudoku grid:
5 1 7 6 9 8 2 3 4
2 8 9 1 3 4 7 5 6
3 4 6 2 7 5 8 9 1
6 7 2 8 4 9 3 1 5
1 3 8 5 2 6 9 4 7
9 5 4 7 1 3 6 8 2
4 9 5 3 6 2 1 7 8
7 2 3 4 8 1 5 6 9
8 6 1 9 5 7 4 2 3
```

## Customization

You can change the hardcoded `grid` variable in the script to solve other puzzles. Use `0` for empty cells.

## License

MIT License
