# Pathfinding Visualizer

This tool visualizes various pathfinding algorithms. I built it out of my interest in these algorithms, and I hope you enjoy experimenting with it. Check it out here: [Pathfinding Visualizer](https://shashwatmurawala-pathvisualizer.netlify.app/)

## Supported Algorithms

- **Dijkstra's Algorithm** (weighted): Guarantees the shortest path.
- **A* Search** (weighted): Fastest and most accurate using heuristics.
- **Greedy Best-first Search** (weighted): A faster, heuristic-heavy A* variant; does not guarantee the shortest path.
- **Swarm Algorithm** (weighted): Combines Dijkstra's and A*; does not guarantee the shortest path.
- **Convergent Swarm Algorithm** (weighted): Faster, heuristic-heavy version of Swarm; no guarantee for the shortest path.
- **Bidirectional Swarm Algorithm** (weighted): Runs Swarm from both sides; no shortest-path guarantee.
- **Breadth-first Search** (unweighted): Guarantees the shortest path.
- **Depth-first Search** (unweighted): Does not guarantee the shortest path.

It also includes a **Recursive Division** Maze Generation algorithm.

## About the Swarm Algorithm

The Swarm Algorithm, co-developed with Hussein Farah, blends Dijkstra's and A* by exploring nodes around the start while considering the target node’s distance. It adjusts based on both the start and target distances, creating a triangular path. The name “Swarm” reflects its potential use in games, where a character prioritizes tracking a target while watching for nearby enemies.
