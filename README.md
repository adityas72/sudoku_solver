# Sudoku Solver in Python

## Overview
This is a Python program that solves Sudoku puzzles using a backtracking algorithm. It efficiently finds the correct solution for a given Sudoku grid.

## Features
- Solves 9x9 Sudoku puzzles
- Uses a backtracking algorithm for an optimal solution
- Can handle partially filled Sudoku grids
- Prints the solved Sudoku board

## How to Run
1. Clone this repository:
   ```sh
   git clone https://github.com/adityas72/sudoku_solver.git
   ```
2. Navigate to the project directory:
   ```sh
   cd sudoku_solver
   ```
3. Run the Python script:
   ```sh
   python main.py
   ```

## Usage
1. Ensure the Sudoku puzzle is correctly defined in `main.py`.
2. Run the script to solve the puzzle.
3. The program will output the solved Sudoku grid.

## Example
### Input Sudoku Grid (Inside `main.py`)
```
[[5, 3, 0, 0, 7, 0, 0, 0, 0],
 [6, 0, 0, 1, 9, 5, 0, 0, 0],
 [0, 9, 8, 0, 0, 0, 0, 6, 0],
 [8, 0, 0, 0, 6, 0, 0, 0, 3],
 [4, 0, 0, 8, 0, 3, 0, 0, 1],
 [7, 0, 0, 0, 2, 0, 0, 0, 6],
 [0, 6, 0, 0, 0, 0, 2, 8, 0],
 [0, 0, 0, 4, 1, 9, 0, 0, 5],
 [0, 0, 0, 0, 8, 0, 0, 7, 9]]
```
### Output Sudoku Grid
```
[[5, 3, 4, 6, 7, 8, 9, 1, 2],
 [6, 7, 2, 1, 9, 5, 3, 4, 8],
 [1, 9, 8, 3, 4, 2, 5, 6, 7],
 [8, 5, 9, 7, 6, 1, 4, 2, 3],
 [4, 2, 6, 8, 5, 3, 7, 9, 1],
 [7, 1, 3, 9, 2, 4, 8, 5, 6],
 [9, 6, 1, 5, 3, 7, 2, 8, 4],
 [2, 8, 7, 4, 1, 9, 6, 3, 5],
 [3, 4, 5, 2, 8, 6, 1, 7, 9]]
```

## Requirements
- Python 3.x

## Contributing
Feel free to fork this repository and contribute improvements.

## License
This project is open-source and available under the MIT License.

