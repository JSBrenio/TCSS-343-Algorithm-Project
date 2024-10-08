# TCSS-343-Algorithm-Project

## Demo
[Project Demo](https://jsbrenio.github.io/TCSS-343-Algorithm-Project/)

## Project Overview
I plan on exploring the A* algorithm used in graphs and pathfinding through code and finding how fast A* is with different implementations. These different implementations are mainly the change in heuristics used to calculate distances between nodes, such as:

- Manhattan Distance
- Euclidean Distance
- Chebyshev Distance
- Octile Distance
- No heuristic (effectively Dijkstra's Algorithm)

I intend to implement the algorithm in JavaScript and track the execution time, number of operations, node count, and visualization of the algorithm’s path to a target node through front-end code. I also want to explore the effectiveness of the A* algorithm in different environments, such as varying maze configurations, noting which heuristic performs best in each maze from its statistics. I will use these statistics to generate graphs to compare the performance of the A* algorithm.

I think the A* algorithm, when implemented with different heuristics, will have varying levels of efficiency in terms of execution time and nodes explored. Specifically, heuristics that more accurately estimate the distance to the goal node will generally result in faster pathfinding times and fewer nodes explored, especially in maze configurations where paths are obstructed or labyrinthine.

Since this is my first time learning and using JavaScript, I will need to have simple HTML and CSS elements in my project. I will probably use graphics libraries for the front-end code to streamline the front-end development process since my focus is on the algorithm implementation. I will use a basic grid layout for the algorithm and, if possible, add the ability for diagonal movement for even better pathfinding efficiency.

### References:
- https://theory.stanford.edu/~amitp/GameProgramming/AStarComparison.html
- https://www.redblobgames.com/pathfinding/grids/graphs.html
- https://theory.stanford.edu/~amitp/GameProgramming/Heuristics.html
- https://en.wikipedia.org/wiki/A*_search_algorithm
- https://www.redblobgames.com/pathfinding/a-star/introduction.html
- https://www.redblobgames.com/pathfinding/a-star/implementation.html
