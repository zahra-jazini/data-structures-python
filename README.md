# data-structures-python
# BFS Pathfinding Algorithm

This project implements the **Breadth-First Search (BFS)** algorithm to find the shortest path in a 2D grid. The grid consists of free and blocked cells, represented by `0` (free) and `1` (blocked), respectively.

## Features:
- **BFS Algorithm**: Used to explore the grid and find the shortest path from a given start point to an endpoint.
- **Grid Representation**: The grid is represented as a 2D array, where free cells are `0` and blocked cells are `1`.
- **Dynamic Pathfinding**: The algorithm explores all possible paths using BFS to ensure the shortest path is found.

## How it Works:
1. **Start & End Points**: The starting point is `(0, 0)` and the end point is `(3, 3)`.
2. **Direction Handling**: The algorithm can move up, down, left, or right.
3. **Queue Management**: BFS uses a queue to explore each cell in layers, ensuring that the shortest path is found in an unweighted grid.
4. **Path Reconstruction**: Once the destination is reached, the algorithm backtracks to reconstruct the shortest path.

## Example Output:Path: [(0, 0), (1, 0), (2, 0), (3, 0), (3, 1), (3, 2), (3, 3)]

# Implementing Data Structures (Arrays, Stacks, Queues, Linked Lists)
# پیاده‌سازی ساختمان داده‌های ابتدایی مانند آرایه‌ها، پشته‌ها، صف‌ها و لیست‌های پیوندی در Python. 
# This project includes basic data structures implementation like arrays, stacks, queues, and linked lists in Python. The goal is to understand the core functionality of each data structure and how to perform basic operations like insertion, deletion, and traversal.

# Binary Search Algorithm
This project demonstrates the Binary Search Algorithm with a visual representation of each step of the search process. Binary search is a highly efficient algorithm for finding an element in a sorted array with a time complexity of O(log n). The visualization helps to understand how the search narrows down the potential search space by halving it at each step. The project uses Python and Matplotlib to display the dynamic process of binary search, with the current middle element highlighted at each step.
