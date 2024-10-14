# Algorithm Implementations

This repository contains implementations of various algorithms and data structures, focusing on classical computer science problems. The algorithms are implemented in Python and cover a range of topics, including graph theory, sorting, dynamic programming, and backtracking.

## Table of Contents

1. [Minimum Cost Spanning Tree](#minimum-cost-spanning-tree)
   - [Kruskal's Algorithm](#kruskals-algorithm)
   - [Prim's Algorithm](#prims-algorithm)
2. [Sorting Algorithms](#sorting-algorithms)
   - [Merge Sort](#merge-sort)
   - [Quick Sort](#quick-sort)
3. [Dynamic Programming](#dynamic-programming)
   - [Bellman-Ford Algorithm](#bellman-ford-algorithm)
   - [Traveling Salesman Problem (Dynamic Programming)](#traveling-salesman-problem-dynamic-programming)
4. [Divide and Conquer](#divide-and-conquer)
   - [Maximum and Minimum in an Array](#maximum-and-minimum-in-an-array)
5. [Backtracking](#backtracking)
   - [N-Queens Problem](#n-queens-problem)
6. [Branch and Bound](#branch-and-bound)
   - [Traveling Salesman Problem (Branch and Bound)](#traveling-salesman-problem-branch-and-bound)

## Minimum Cost Spanning Tree

### Kruskal's Algorithm
- **Description**: Finds the Minimum Spanning Tree for a connected undirected graph by sorting the edges and adding them one by one.
- **Usage**: See `kruskal.py`.

### Prim's Algorithm
- **Description**: Builds the Minimum Spanning Tree by starting from a vertex and expanding the tree by adding the minimum edge connecting the tree to a vertex outside it.
- **Usage**: See `prim.py`.

## Sorting Algorithms

### Merge Sort
- **Description**: A divide and conquer algorithm that sorts an array by dividing it into halves, sorting them, and merging them back.
- **Usage**: See `merge_sort.py`.

### Quick Sort
- **Description**: An efficient sorting algorithm that uses a pivot to partition the array and recursively sort the partitions.
- **Usage**: See `quick_sort.py`.

## Dynamic Programming

### Bellman-Ford Algorithm
- **Description**: Computes the shortest paths from a single source vertex to all other vertices in a weighted graph.
- **Usage**: See `bellman_ford.py`.

### Traveling Salesman Problem (Dynamic Programming)
- **Description**: Solves the TSP using dynamic programming to find the shortest possible route that visits each city once and returns to the origin city.
- **Usage**: See `tsp_dynamic.py`.

## Divide and Conquer

### Maximum and Minimum in an Array
- **Description**: Finds the maximum and minimum elements in an array using a divide and conquer strategy.
- **Usage**: See `max_min.py`.

## Backtracking

### N-Queens Problem
- **Description**: Solves the N-Queens problem using backtracking, placing N queens on an N×N chessboard so that no two queens threaten each other.
- **Usage**: See `n_queens.py`.

## Branch and Bound

### Traveling Salesman Problem (Branch and Bound)
- **Description**: Solves the TSP using branch and bound techniques to find the optimal solution.
- **Usage**: See `tsp_branch_bound.py`.

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/phcoder05/allinonealgorithm.git
