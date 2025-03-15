# Pacman Search Project

## Acknowledgments
I collaborated with Stella Miliatis, William Wallace, and Jose Salazar on this project. Special thanks to the UC Berkeley CS188 staff for providing the framework.

## Overview
This project is part of the UC Berkeley AI course and focuses on implementing search algorithms to navigate Pacman through different mazes. The goal is to explore and apply fundamental search techniques to solve pathfinding problems efficiently.

## Features
- Implementation of various search algorithms
- Navigation of Pacman through different maze environments
- Analysis of algorithm efficiency and performance

## Installation & Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/pacman-search.git
   cd pacman-search
   ```
2. Ensure you have Python 3 installed.
3. Run the project using:
   ```sh
   python pacman.py -l mediumMaze -p SearchAgent -a fn=bfs
   ```

## Usage
You can test different search algorithms using the following commands:
- **Depth-First Search (DFS):**
  ```sh
  python pacman.py -l mediumMaze -p SearchAgent -a fn=dfs
  ```
- **Breadth-First Search (BFS):**
  ```sh
  python pacman.py -l mediumMaze -p SearchAgent -a fn=bfs
  ```
- **Uniform Cost Search (UCS):**
  ```sh
  python pacman.py -l mediumMaze -p SearchAgent -a fn=ucs
  ```
- **A* Search (A*):**
  ```sh
  python pacman.py -l mediumMaze -p SearchAgent -a fn=astar,heuristic=manhattanHeuristic
  ```

## Algorithms Implemented
- Depth-First Search (DFS)
- Breadth-First Search (BFS)
- Uniform Cost Search (UCS)
- A* Search (A*) with heuristics

## Files Description
- `search.py` – Implementation of search algorithms
- `searchAgents.py` – Defines agents using search algorithms
- `pacman.py` – Runs the Pacman game
- `layout/` – Contains different maze configurations

## Credits
This project is part of UC Berkeley's CS188: Introduction to Artificial Intelligence course.

## License
This project is for educational purposes and follows the UC Berkeley course guidelines.
