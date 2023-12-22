# Sudoku Solver GUI

This project implements a simple Sudoku Solver with a graphical user interface (GUI) using Python and Tkinter.


https://github.com/SnehShah17/Sudoku_Solver/assets/75317219/98183053-2613-45e4-beec-3d845f9aed1e




## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Sudoku Solver Algorithm](#sudoku-solver-algorithm)
- [Usage](#usage)
- [Installation](#installation)
- [Dependencies](#dependencies)

## Introduction

This Sudoku Solver allows users to input a Sudoku puzzle through a 9x9 grid and provides functionality to solve the puzzle. The solver logic is implemented in a separate module, `solver.py`, and the GUI is built using Tkinter in `sudoku_solver_app.py`.

## Features

- User-friendly GUI for inputting Sudoku puzzles
- Solve button to find the solution to the puzzle
- Clear button to reset the input
- Feedback messages for errors or successful puzzle solving

## Sudoku Solver Algorithm

The Sudoku solving algorithm is implemented in the `solver.py` file. It uses a backtracking algorithm to find a solution to the puzzle. The algorithm checks whether a number can be safely placed in a given cell by ensuring it does not violate the rules of Sudoku.

```python
N=9

def isSafe(sudoku, row, col, num):
    # ... (checks whether it's safe to place 'num' in the specified cell)

def solveSudoku(sudoku, row, col):
    # ... (backtracking algorithm to solve the Sudoku puzzle)

def solver(sudoku):
    # ... (main function that returns the solved puzzle or "no" if no solution exists)
```

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/SnehShah17/Sudoku_Solver.git
   cd sudoku-solver
   ```

2. Run the script:
   ```bash
   python sudoku_solver_app.py
   ```

   If you're using Python 3:
   ```bash
   python3 sudoku_solver_app.py
   ```

3. Fill in the Sudoku puzzle numbers in the provided grid.

4. Click the "Solve" button to find the solution.

5. Use the "Clear" button to reset the input.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/sudoku-solver.git
   cd sudoku-solver
   ```

2. Run the script:
   ```bash
   python sudoku_solver_app.py
   ```

   If you're using Python 3:
   ```bash
   python3 sudoku_solver_app.py
   ```

## Dependencies

- Python 3
- Tkinter

Install dependencies using:
```bash
pip install tk
```
