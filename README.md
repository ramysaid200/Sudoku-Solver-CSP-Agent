# Sudoku Solver Agent using CSP and Backtracking Search

## Overview
This project features an AI agent designed to solve Sudoku puzzles by modeling them as a Constraint Satisfaction Problem (CSP). The primary approach utilizes a recursive Backtracking Search algorithm enhanced by the Minimum Remaining Values (MRV) heuristic to intelligently navigate the state space and find solutions efficiently. 

## Key Features
* **Intelligent Cell Selection (MRV Heuristic):** Minimizes the search space by scanning the board and dynamically calculating the legal options for each empty cell, prioritizing cells with the fewest remaining options.
* **Constraint Validation:** Enforces the three fundamental Sudoku rules before making any assignment: no repeating numbers in the same row, column, or local 3x3 sub-grid.
* **High Performance on Complex Grids:** While standard backtracking can get trapped on heavily constrained puzzles (taking over 5 minutes on an "Evil Grid"), the MRV-optimized agent detects constraints immediately and solves the same puzzle in approximately 4.42 seconds—making it roughly 78 times faster.
* **Local Beam Search Exploration:** Includes a supplementary "Free Topic" section that explores the Local Beam Search algorithm. The project analyzes its theoretical application to Sudoku and successfully demonstrates its practical use on the classic 8-Queens problem.

## Technologies & Tools
* **Programming Language:** Python 3.
* **Development & Prototyping:** Google Colab for cloud-based real-time collaboration, alongside Visual Studio Code (VS Code) and PyCharm.

## Team Members
* Ramy Said Eliwa Elsayed
* David George Helmy Ekladious
* Ahmed Mohamed Abdelrazik

## Academic Context
This project was developed for the Artificial Intelligence (CCE414) course under the Communication and Computer Engineering Program.
