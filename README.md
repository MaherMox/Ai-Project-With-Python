# N-Queens AI Solver 🏰♛

A Python-based **N-Queens Solver** that uses **multiple AI search algorithms** with a **Tkinter graphical interface** to visualize solutions on a chessboard.

## 📌 Overview
The N-Queens problem is a classic chess-based puzzle:
> Place N queens on an N×N chessboard so that no two queens threaten each other.

This project implements **four solving algorithms**:
- **Backtracking**
- **Best-First Search**
- **Hill Climbing**
- **Genetic Algorithm** (with fitness plot)

The program allows you to:
- Select the board size `N` (4 ≤ N ≤ 100)
- Choose an algorithm
- Visualize the solution on a chessboard

---

## 🚀 Features
- **Multiple AI algorithms** for solving N-Queens
- **Interactive Tkinter GUI**
- **Dynamic chessboard rendering**
- **Fitness visualization** for Genetic Algorithm
- Supports **custom board sizes** up to 100×100

---

## 🛠 Technologies Used
- **Python 3**
- **Tkinter** (GUI)
- **Matplotlib** (fitness plotting for Genetic Algorithm)
- **Heapq & Random** (algorithm implementations)

---

## 📂 Project Structure
n-queens-ai-solver/
│── backtracking.py # Backtracking algorithm
│── best_first.py # Best-First Search algorithm
│── hill_climbing.py # Hill Climbing algorithm
│── genetic.py # Genetic Algorithm + plotting
│── main.py # Tkinter GUI entry point
│── README.md # Project documentation

yaml
Copy
Edit

---

## 🔧 Installation & Usage
1. **Clone the repository**
```bash
git clone https://github.com/your-username/n-queens-ai-solver.git
cd n-queens-ai-solver
