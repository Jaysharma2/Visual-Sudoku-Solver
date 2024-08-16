# Visualizing Backtracking Algorithm with a Python-Based Sudoku Solver


## Overview

This project provides a Python-based Sudoku solver utilizing the Backtracking Algorithm. The solver efficiently fills a 9×9 Sudoku grid, ensuring every row, column, and 3×3 subgrid contains all digits from 1 to 9 without repetition. The implementation optimizes solution times to under one second for most puzzles and allows users to input puzzles as an 81-character string.

## Features

- **Efficient Backtracking Algorithm**: Solves Sudoku puzzles quickly by exploring potential solutions and backtracking when necessary.
- **User-Friendly Interface**: Accepts Sudoku puzzles as an 81-character string and displays solutions.
- **Customizable**: Easily modify and test different puzzles. Extend functionality with planned features for alternative algorithms and Machine Learning techniques.

## Requirements

- Python 3.0 or higher (Python 2.2+ is also supported)
  
## Installation

1. **Download** the repository as a ZIP file and extract it to your machine.
2. **Run** the `solve.py` file using Python:
   ```bash
   python solve.py
   ```
   - For Linux or Mac users, modify the line specified in the comments (line #3 in `solve.py`) to ensure compatibility.
   - To speed up processing, consider commenting out lines #28 to #30 if you want to skip the visualization part.

## Usage

1. **Input**: Edit the `puzzle0` and `solution0` variables in `solve.py` to test different Sudoku puzzles. Demo puzzles and their solutions are available in `puzzles.py` and `solutions.py`.
2. **Execution**: Run the `solve.py` script to view solutions for the given puzzles.

## Future Work

- **Algorithm Exploration**: Investigate alternative solving methods such as Stochastic Search, Constraint Programming, and Exact Cover.
- **Machine Learning Integration**: Utilize datasets from Kaggle to explore Machine Learning techniques for solving Sudoku puzzles.
- **Augmented Reality**: Develop Convolutional Neural Networks and AR technology to detect and solve Sudoku puzzles from images.


## License

This project is open-source and available for both non-commercial and commercial use. For more details, please refer to the [license file](LICENSE).
