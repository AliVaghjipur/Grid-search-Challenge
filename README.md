# Grid-search-Challenge
This is a simple code regarding moving through a grid like city with roads (0) and obstacles (1), trying to reach a goal grid box.

Detailed description of the task is given with the code as well as here below:

Shortest Path in a City Grid (Graph Problem)

Imagine you're developing a navigation system for an autonomous vehicle in a city. The car needs to find the shortest path from its starting location to a destination. The city is represented by a grid, where some cells are roads (you can move through them), and others are obstacles (you can't move through them).

Problem:
* You're given a 2D grid grid of size N x M where 0 represents an empty road, and 1 represents an obstacle.
* You can move up, down, left, or right, but not diagonally.
* Your task is to write a function that returns the minimum number of moves to get from the top-left corner of the grid (0,0) to the bottom-right corner (N-1, M-1). If it's not possible to reach the destination, return -1.
