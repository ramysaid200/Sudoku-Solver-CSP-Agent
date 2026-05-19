# Sudoku Solver Agent using CSP and Backtracking Search

## Overview
[cite_start]This project details the development of an AI agent designed to solve Sudoku by modeling it as a Constraint Satisfaction Problem (CSP)[cite: 16]. [cite_start]Built with Python 3, the agent intelligently navigates the state space using a recursive Depth-First Search (DFS) algorithm, enhanced by Backtracking and the Minimum Remaining Values (MRV) heuristic[cite: 45, 52].

## Key Features
* [cite_start]**Intelligent Cell Selection:** Utilizes the MRV heuristic to significantly minimize the search space by scanning and calculating the legal options for each empty cell[cite: 56, 57].
* [cite_start]**Constraint Validation:** Enforces standard Sudoku rules across rows, columns, and 3x3 sub-grids before making variable assignments[cite: 68, 69, 70, 71].
* [cite_start]**Performance Optimization:** The MRV-optimized agent is capable of solving highly constrained grids (such as the "Evil Grid") in a fraction of a second, proving to be roughly 78 times faster than standard backtracking methods on complex puzzles[cite: 107, 109].
* [cite_start]**Local Beam Search Exploration:** Includes a supplementary study on Local Beam Search and its application to the 8-Queens problem, detailing its memory efficiency and limitations regarding local maxima[cite: 714, 773, 794].

## Technologies Used
* [cite_start]Python 3 [cite: 45]
