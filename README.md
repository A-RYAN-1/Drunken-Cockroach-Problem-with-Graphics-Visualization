# Visualizing a Drunken Cockroach Path using Computer Graphics
This project simulates the Drunken Cockroach Problem, where a cockroach moves randomly in a grid, with each step representing a random direction (up, down, left, or right). The goal is to observe its wandering behavior and track its path over time. The program uses graphics visualization to display the cockroach's movement in real-time, providing a dynamic and engaging way to study random walk problems in a visual format. Ideal for those interested in algorithmic simulations, random walks, and graphical representation of mathematical concepts.

## Problem Statement
The project aims to visualize the path of a drunken cockroach within a matrix using C++ and the graphics.h library. The cockroach's path is determined using Depth-First Search Algorithm (DSA), and the graphical representation is achieved through the graphics.h library. The program allows the user to input the starting cell coordinates (x, y) for the cockroach within the matrix.

## Domain
Algorithm Visualization:
Implementation and visualization of a pathfinding algorithm (e.g., Depth-First Search).
Simulation of the movement of a drunken cockroach within a matrix.
Computer Graphics:
Utilization of the graphics.h library for graphical representation.
Creation of an interactive display for the matrix, cockroach path, and step count.

## Code Review
Data structures
1. Matrix (2D Array)<br>
Represents a grid or matrix where the drunken cockroach moves.
Each cell in the matrix corresponds to a tile on the graphical screen.
2. Linked List<br>
Represents a linear linked list to store and manage the path information of the drunken cockroach.<br>

Algorithms 
1. Backtracking<br>
Choose: Make a choice at the current decision point.<br>
Explore: Recursively explore the consequences of the choice made.<br>
Undo: If the choice leads to a dead end, undo the choice and backtrack to the previous decision point.<br>
Continue: Continue the process until a solution is found or all possibilities are explored.
2. Bubble Sort<br>
After obtaining the path in the linked list, a simple bubble sort algorithm is used to sort the linked list based on the step number. The purpose is to organize the steps in ascending order for better visualization.

## Conclusion
In conclusion, this C++ program seamlessly integrates algorithmic problem-solving with graphical representation to visualize the path of a cockroach on an 8x8 chessboard. The implementation employs backtracking to solve the Knight's Tour problem, determining a valid sequence of moves for the cockroach. The use of the graphics.h library facilitates an engaging and interactive display of the cockroach's journey, enhancing the understanding of the algorithm's execution. Through this project, a synergy of data structures, algorithms, and graphics functions creates an educational and visually appealing demonstration of problem-solving in a programming context.


## Project Images
![Drunken Cockroach 1](https://github.com/user-attachments/assets/946a14cc-14d2-428e-8992-5e8b3e16d5fc)
