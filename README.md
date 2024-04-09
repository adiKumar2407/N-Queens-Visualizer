
# N-Queens Visualizer
Welcome to the N-Queens Visualizer repository! This project is dedicated to solving the N-Queens puzzle using recursion and providing a visual representation of the solutions.

# Introduction
The N-Queens puzzle is a classic problem in computer science and combinatorial optimization. The goal is to place N chess queens on an N×N chessboard in such a way that no two queens threaten each other. This means that no two queens should share the same row, column, or diagonal.

This project not only solves the puzzle but also provides a visual representation of the solutions, making it easier to understand and analyze the placement of queens on the board.

# Features
Recursive backtracking algorithm to find all solutions to the N-Queens puzzle.
Visual representation of the solutions using a graphical user interface (GUI).
Customizable board size to accommodate different variations of the puzzle.

# Demo
Website - https://incandescent-gingersnap-971aa5.netlify.app/

# Algorithm

Approach

. Start with an empty chessboard.
. Place a queen in the first row.
. Move to the next row and place a queen in a safe position.
. Repeat step 3 until all queens are placed or no safe position is found.
. If all queens are placed, a solution is found. If not, backtrack and try a different position for the previous queen.
. Repeat steps 3-5 until all solutions are found.

