# 🧩 Sudoku Solver using CSP (AC-3 + Backtracking)

This project implements a Sudoku solver using **Constraint Satisfaction Problem (CSP)** techniques in Python.

## 🚀 Features

* AC-3 Algorithm (Arc Consistency)
* Backtracking Search
* MRV (Minimum Remaining Values heuristic)
* Forward Checking
* Supports multiple difficulty levels

## 📂 Input Files

The solver reads Sudoku boards from text files:

* easy.txt
* medium.txt
* hard.txt
* veryhard.txt

Each file contains a 9x9 Sudoku grid where:

* `0` represents empty cells

## ▶️ How to Run

```bash
python sudoku_solver.py
```

## 🧠 Algorithms Used

### 1. AC-3 (Arc Consistency)

Reduces domains before search.

### 2. Backtracking

Searches for solution recursively.

### 3. MRV Heuristic

Selects variable with smallest domain.

### 4. Forward Checking

Eliminates invalid values early.

## 📊 Output

* Solved Sudoku board
* Backtracking calls
* Backtracking failures

## 🎯 Purpose

This project is designed for learning **Artificial Intelligence (CSP problems)**.

## 👩‍💻 Author

Amna Noor
# sudoku-csp-solver
