# Tetris Console Game

## Overview
This game is designed to be executed on Windows OS.
This is a simple Tetris game implemented in C++ for the console. The game features falling tetrominoes, rotation, movement, line clearing, and scoring. The game runs within a terminal window and utilizes basic console manipulation for display.

## Features
- **Tetromino Shapes**: Includes standard Tetris pieces (I, O, T, S, Z, L, J).
- **Movement**: Move left, right, and down.
- **Rotation**: Rotate pieces clockwise.
- **Gravity**: Pieces automatically fall over time.
- **Line Clearing**: Completed rows disappear, and the score increases.
- **High Score Tracking**: Stores and updates the highest score.
- **Game Over Detection**: Ends the game when no space is available for a new piece.

## Controls
- **Left Arrow (←)**: Move tetromino left.
- **Right Arrow (→)**: Move tetromino right.
- **Down Arrow (↓)**: Move tetromino down faster.
- **Up Arrow (↑)**: Rotate tetromino.
- **Spacebar**: Instantly drop tetromino to the lowest possible position.

## Compilation & Execution
### Requirements
- **C++ Compiler** (e.g., MinGW for Windows, g++ for Linux/Mac)
- **Windows OS** (uses Windows-specific console manipulation functions)

### Compile & Run
```sh
 g++ tetris.cpp -o tetris.exe
 tetris.exe
```

## How It Works
1. **Initializing the Grid**: A 10x20 grid is created to store tetromino positions.
2. **Spawning Tetrominoes**: Random tetrominoes appear at the top of the grid.
3. **User Input**: Arrow keys and spacebar allow movement and rotation.
4. **Collision Detection**: Ensures tetrominoes move within bounds and stack correctly.
5. **Clearing Lines**: When a row is full, it is cleared, and the score increases.
6. **Game Over**: If a new tetromino cannot fit, the game ends.

## Credits
- https://youtu.be/wVYKG_ch4yM?si=mr6fMjFn7TqR5Xpw
-  https://www.geeksforgeeks.org/.

## Contributions
- Aryan Kanani.
   Code Developement and README file
- Shivam Thanki.
   Code Developement and Rectification of errors
- Arjunsinh Vaghela.
   Code Developement and OPtimization of code





