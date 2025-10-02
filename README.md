# Ray Casting 3D Maze Game

**Developer:** Anukrati Chaturvedi

## What is this?

A 3D maze game built from scratch using ray casting graphics technique. The game renders a 3D perspective entirely using vertical lines - the closer you are to a wall, the taller the line appears. Think classic Wolfenstein 3D!

## Key Features

- **First-person 3D maze navigation** with smooth movement
- **Procedurally generated mazes** - every game is different
- **Visual enhancements** including:
  - Colored walls with distance-based shading
  - Sky and floor gradients
  - Floor tiles marking the exit
  - Reflective surfaces
  - Half-height walls for variety

## Tech Stack

This project uses only three Python libraries:

- **NumPy** - For mathematical calculations and array operations
- **Matplotlib** - For rendering the graphics
- **Keyboard/Pynput** - For player controls

## How to Play

- **Arrow Keys**: Move forward/backward and rotate left/right
- **Goal**: Navigate through the randomly generated maze to reach the blue exit tiles
- **Esc**: Quit the game

## Project Versions

### Version 1.0 - The Basics
Simple ray casting with basic walls, player movement, and random maze generation.

### Version 2.0 - Enhanced Graphics
Added reflective surfaces, gradient backgrounds, improved shading, half-height walls, and checkerboard floor patterns.

## Technical Highlights

- Pure Python implementation with minimal dependencies
- Ray casting algorithm that shoots 60 rays per frame
- Distance-based perspective rendering
- Procedural maze generation using random walker algorithm
- Real-time rendering with matplotlib

## What I Learned

Building this project helped me understand:
- How old-school 3D games worked before modern GPUs
- Ray casting vs ray tracing differences
- Basic game loop architecture
- Procedural content generation
- Performance optimization with Python

---

*This is a learning project exploring classic computer graphics techniques. Perfect for understanding how 3D rendering works at a fundamental level!*