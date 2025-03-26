# Tetris_Game
Here, we have uploaded our tetris game we created for our DS-OOPs course.
A classic Tetris game implementation in C++ that runs in the Windows console with colored tetrominoes and sound effects.

## Features

- Classic Tetris gameplay with 7 standard tetromino shapes (I, O, T, S, Z, J, L)
- Color-coded pieces using console text attributes
- Sound effects for piece placement and hard drops
- Scoring system with level progression
- Line clearing with animation
- Pause functionality
- High score tracking
- Start and game over screens
- Smooth controls with keyboard input

## Controls

- Left Arrow (←): Move piece left
- Right Arrow (→): Move piece right
- Down Arrow (↓): Soft drop (faster falling)
- Up Arrow (↑): Rotate piece
- Spacebar: Hard drop (instant fall)
- ESC: Toggle pause

## Gameplay

- Pieces fall automatically at increasing speeds based on level
- Score increases with each soft drop (1 point) and line clear (100 points)
- Level increases every 10 lines cleared
- Game speed increases with each level
- Game ends when pieces stack to the top

## Requirements

- Windows operating system (uses Windows.h for console manipulation)
- C++ compiler supporting C++11 or later
- Standard C++ libraries

## Installation

1. Clone or download the repository
2. Compile the source code using a C++ compiler:

```
g++ tetris.cpp -o tetris
```

1. Run the executable:

```
tetris.exe
```

## Building

The game uses:

- `<iostream>` for console I/O
- `<vector>` for game board and piece representation
- `<conio.h>` for keyboard input
- `<windows.h>` for console manipulation and sound
- `<ctime>` for random piece generation

## How to Play

2. Run the executable
3. Press any key at the start screen to begin
4. Use arrow keys to move and rotate pieces
5. Spacebar for instant drops
6. ESC to pause/resume
7. Clear lines to score points
8. Game ends when pieces reach the top
9. Press any key at game over screen to exit

## Scoring

- Soft drop: 1 point per block
- Line clear: 100 points per line
- Level up: Every 10 lines cleared
- Speed increases with each level

## Known Issues

- Console window must be large enough to display the full game board
- Colors may display differently depending on console settings
- Sound requires Windows sound capabilities

## Future Improvements

- Add next piece preview
- Implement hold piece functionality
- Add different game modes
- Include background music
- Add difficulty selection
- Improve game over animation

## Created By

**Team Name** - Code Slayers

**Team Members**

1. Neel Khatri - 202401093
2. Kavya Bhojwani - 202401090
3. Kavish Inani - 202401089
4. Manal Patel - 202401112
