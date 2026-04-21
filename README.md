# maze-generator
# Maze Generator - CEEP Project

An interactive web application demonstrating data structures through maze generation and solving algorithms.

## Features
- **Three Maze Generation Algorithms**: DFS (Stacks), Prim's (Trees), Kruskal's (Graphs)
- **Maze Solver**: BFS algorithm for shortest path finding
- **Real-time Visualization**: Watch algorithms work step-by-step
- **Performance Analysis**: Compare algorithm efficiency
- **Export Functionality**: Download mazes as PNG or JSON

## Data Structures Used
- **Graphs** - Maze representation as connected nodes
- **Trees** - Spanning tree structure (Prim's algorithm)
- **Stacks** - Backtracking in DFS
- **Queues** - BFS for pathfinding

## Technologies
- React 18.2.0
- TailwindCSS 3.3.2
- shadcn/ui Components
- Canvas API for visualization

## How to Run
1. Clone this repository
2. Install dependencies: `npm install`
3. Start development server: `npm run dev`
4. Open http://localhost:5173 in your browser

## Project Structure
- `/src/pages` - Main pages (MazeGenerator, About, Gallery)
- `/src/components` - Reusable components
- `/src/utils` - Maze algorithms and solver logic

## Algorithms Explained
- **DFS**: Uses stack for backtracking, creates long winding paths
- **Prim's**: Grows maze from starting cell, creates balanced mazes
- **Kruskal's**: Connects random cells while avoiding loops
- **BFS**: Finds shortest path through the maze

## Author
[Your Name] - B.Tech 1st Year CEEP Project

## License
MIT
