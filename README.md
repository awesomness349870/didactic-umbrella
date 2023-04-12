# didactic-umbrella

## Introduction
This is an ongoing project to implement the game "Rush Hour" in Python, where the player tries to resolve a traffic jam by moving cars on a grid, with the objective of getting a specific car to the exit. 

The code currently uses a naive BFS search, treating each board state as a node in a graph, to find a solution. Although this algorithm guarantees that the shortest possible solution is found, the computational demand is rather high and thus the computer can not quickly solve harder or larger puzzles. On the "expert" levels provided by the manufacturer, the program currently experiences runtimes from 1s to 4s.

## TO-DO
-Reduce runtime of current algorithm through improvements in code and implementation
-Employ and explore heuristics (A*) to increase efficiency in a more global manner
-Write code to generate difficult test-cases that can evaluate effect of various heuristics
  -Current generator code has multiple major bugs and usually produces trivial puzzles
-Implement graphics
