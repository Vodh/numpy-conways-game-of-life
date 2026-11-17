# Conway's Game of Life

A Python implementation of Conway's Game of Life, built as a beginner project while learning NumPy.

## About
Conway's Game of Life is a cellular automaton where cells evolve over generations based on the state of their neighbours.

## Technologies Used
- Python
- NumPy
- Time
- IPython

## Rules
1. A living cell with fewer than 2 living neighbours dies.
2. A living cell with 2 or 3 living neighbours survives.
3. A living cell with more than 3 living neighbours dies.
4. A dead cell with exactly 3 living neighbours becomes alive.

## Features
- 2D NumPy array representation of the board.
- Neighbour counting using nested loops.
- Boundary checking.
- Generation-by-generation updates.
- Custom starting patterns.

## How to Run

Install dependencies:

```bash
pip install numpy ipython
```

Run:

```bash
python game_of_life.py
```

## Learning Goals
This project helped me understand:
- NumPy arrays and indexing.
- Array copying using `.copy()`.
- Nested loops.
- Conditional statements.
- Basic simulation logic.