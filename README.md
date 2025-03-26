# Tetris Game in C++ (Terminal-Based)

## Description
This is a simple terminal-based implementation of the classic Tetris game written in C++. The game runs in the terminal and does not require any external graphics libraries. It makes use of basic programming concepts such as functions, classes, arrays, and standard I/O.

## Features
- Seven classic Tetris pieces (I, O, T, S, Z, L, J)
- Arrow key controls for movement and rotation
- Spacebar for hard drop
- Score tracking based on lines cleared
- Game over screen

## Controls
- **Left Arrow (←)** - Move piece left
- **Right Arrow (→)** - Move piece right
- **Down Arrow (↓)** - Move piece down faster
- **Up Arrow (↑)** - Rotate piece
- *Spacebar (` ` )* - Hard drop
- *Q* - Quit the game

## Requirements
- A C++ compiler (e.g., g++, clang++)
- A terminal that supports ANSI escape sequences

## Compilation & Execution
To compile the program, use the following command:
sh
 g++ tetris.cpp -o tetris -std=c++11

To run the program, use:
sh
 ./tetris


## How to Play
1. Start the game, and a random Tetris piece will appear at the top of the grid.
2. Use arrow keys to move and rotate the piece.
3. Complete horizontal lines to clear them and score points.
4. The game ends when new pieces can no longer be placed.

## Scoring
- *1 Line Cleared* = 100 Points
- *2 Lines Cleared* = 300 Points
- *3 Lines Cleared* = 500 Points
- *4 Lines Cleared (Tetris!)* = 800 Points

## Credits
- https://youtu.be/wVYKG_ch4yM?si=Ed2nSL6_Z28E33eU
- https://www.geeksforgeeks.org/

## Contributions
- Aryan Kanani. Code Developement and README file
- Shivam Thanki. Code Developement and Rectification of errors
- Arjunsinh Vaghela. Code Developement and OPtimization of code
