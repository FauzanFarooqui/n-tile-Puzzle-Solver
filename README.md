# n-tile-Puzzle-Solver

The n-tile puzzle aims to shift n tiles on a board from a starting configuration to a goal configuration, shifting only one tile every step using the 'blank' tile.

Traditional 'AI' search algorithms can be used to play this game.
This is an implementation of the Bidirectional Search algorithm (BDS), which used Breadth-First Search (BFS) from both directions.

Note: This was an assignment completed as part of the Artifical Intelligence course at the Computer Science and Engineering Department at Visvesvaraya National Institute of Technology, Nagpur, India.

To-do:

- This isn't a final implementation, hash tables will be added later.

- Only ~half of all possible state configurations of a n-tile puzzle are reachable from a given configuration. There exists a method to check the whether the goal is reachable from a given start goal or not. This can be implemented for a 'full' solver.
