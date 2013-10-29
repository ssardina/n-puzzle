N-Puzzle
========

Overview
--------

N-Puzzle is a web app for learning about graph-based search algorithms.

This app uses the 8-puzzle to visualise the use of various graph-based search 
algorithms. The 8-puzzle is an instance of the n-puzzle problem, where eight 
tiles are placed on a 3x3 grid. The remaining un-tiled position is an empty
space. Tiles adjacent to the empty space may be moved into that space. The
puzzle is solved by finding a sequence of moves that will transform the initial
state into a given goal state.

An example initial state and goal state are given below:

                 2 3 -                   2 5 3
 Initial state:  4 5 1       Goal state: 4 7 -
                 6 7 8                   6 8 1

N-Puzzle provides five algorithms that can be used to solve the problem:
 - Breadth-first Search (BFS)
 - Depth-first Search (DFS)
 - Iterative Deepening DFS (ID-DFS)
 - Greedy Search
 - A* Search

Since Greedy Search and A* Search are informed search algorithms, three
heuristic functions are also provided:
 - Euclidean distance heuristic
 - Manhattan distance heuristic
 - Tiles-out heuristic

License
-------

N-Puzzle is distributed under the Simplied BSD License. See the LICENSE file
for more information.

History
-------

N-Puzzle is based on the AI-Search Java applet developed at RMIT University by
Vic Ciesielski, James Harland and Peter McDonald. The original applet can found
at: http://www.cs.rmit.edu.au/AI-Search/