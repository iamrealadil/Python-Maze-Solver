# Python Maze Solver

A Python program that solves mazes using Depth-First Search (DFS) with a stack and Breadth-First Search (BFS) with a queue. It tracks explored states, finds the path from start to goal, and visualizes the solution as a PNG image.

# VIDEO DEMO: 

## Features

- Solve mazes using DFS (stack) and BFS (queue)
- Counts and displays the number of explored states
- Visualizes the maze and solution path as an image
- Easy to use with a text-based maze input

## Usage

1. Prepare a maze file (`maze.txt`) with:
   - `A` as the start point
   - `B` as the goal
   - `#` for walls
   - Space (` `) for open paths

2. Run the solver:

```bash
python maze.py maze.txt
