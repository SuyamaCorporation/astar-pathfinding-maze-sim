# A* Pathfinding Algorithm Grid Maze Simulator

An interactive pathfinding visualizer with multiple algorithms and maze generation.

## Features
- Grid 10×10 to 30×30 (default 20×20)
- Click to place: Start (green) → End (red) → Toggle walls
- Drag to paint walls
- Maze generation via recursive backtracker algorithm
- Algorithms: A* Manhattan, A* Euclidean, Dijkstra, BFS
- Animated visualization: Open set (yellow), Closed set (blue), Current (orange), Path (lime)
- Step-by-step mode or continuous animation with 6 speed levels
- Stats: nodes explored, path length, time taken (ms)
- "No path exists" notification
- Color legend
- Clear path (keep walls) and Clear all

## Usage
Open `index.html` in any modern browser. No server required.

## Click Interaction
1. First click → places Start (green cell)
2. Second click → places End (red cell)
3. Subsequent clicks / drag → toggle walls
