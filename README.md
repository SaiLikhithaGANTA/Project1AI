# Project1AI
**please run the code in google colab**
'warp_pipe_destinations': A dictionary that maps the positions of warp pipes to their corresponding destinations.

'walk_cost' and 'pipe_cost': Constants representing the cost of walking and using a warp pipe.

'heuristic(x, y)': A heuristic function that calculates the Manhattan distance between two points 'x' and 'y'. This function is used to estimate the cost from a current position point1 to the goal position point2.

'astar(grid, pipe_destinations, walk_cost, pipe_cost, start, goal)': The main A* search algorithm function. It finds the path from the 'start' position to the 'goal' position on a grid with warp pipes and returns the path as a list of positions.

'neighbors(grid, point)': A helper function that finds neighboring positions from a given point on the grid. It considers positions up, left, down, and right of the current point, excluding any positions blocked by obstacles ('O').

Test case: The code demonstrates the A* algorithm by searching for a path from the 'start' position (0, 0) to the goal position (4, 4)using the 'astar' function. If a path is found, it prints the path positions; otherwise, it prints "No path found."
