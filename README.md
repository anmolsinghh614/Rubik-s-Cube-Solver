# Rubik's Cube Solver

A high-performance, modular Rubik's Cube solver supporting multiple solving algorithms and cube representations, with pattern database heuristics for efficient solving.

---

## Features
- **Multiple Cube Models:**
  - 3D Array, 1D Array, and Bitboard representations
- **Solving Algorithms:**
  - Depth-First Search (DFS)
  - Breadth-First Search (BFS)
  - Iterative Deepening DFS (IDDFS)
  - Iterative Deepening A* (IDA*) with pattern database heuristics
- **Pattern Databases:**
  - Fast heuristic lookup for optimal solving
  - Tools to generate and use pattern databases
- **Extensible & Benchmarkable:**
  - Easily add new models or solvers
  - Compare performance and correctness

---

## Directory Structure
- `main.cpp` — Entry point, demo, and testing
- `Model/` — Cube model implementations (3D, 1D, Bitboard)
- `Solver/` — Solvers (DFS, BFS, IDDFS, IDA*)
- `PatternDatabases/` — Pattern database logic, helpers, and utilities
- `Databases/` — Generated pattern database files

---

## Usage
1. **Build the project** using CMake:
   ```sh
   mkdir build && cd build
   cmake ..
   make
   ```
2. **Run the solver**:
   ```sh
   ./rubiks-cube-solver
   ```
3. **Modify `main.cpp`** to test different models, solvers, or shuffling/solving scenarios.

---

## How It Works
- Choose a cube model (3D, 1D, Bitboard)
- Select a solver (DFS, BFS, IDDFS, IDA*)
- (Optional) Generate/load a pattern database for heuristic solvers
- Shuffle the cube and solve it, printing the solution and stats

---

## Author
**Anmol Singh**

---

## License
This project is for educational and research purposes.