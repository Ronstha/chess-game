# Chess Game
## Overview

This is a feature-rich 2D chess implementation created using C++ and SDL2. The game follows all the standard rules of chess and offers both a classic two-player mode and a puzzle mode to challenge your skills.

## Features

### Game Mode
- Two players can play on the same computer
- Full implementation of chess rules including:
  - Capturing
  - Check and checkmate detection
  - Stalemate detection
  - En passant
- Customizable player names
- Adjustable time limits
- Visual highlighting of legal moves
- Sound effects for moves, captures, check, and checkmate
- Sidebar displaying:
  - Captured pieces
  - Player names
  - Turn indicator
  - Game status
  - Timer (if enabled)

### Puzzle Mode
- Pre-defined chess puzzles to solve
- Hint system
- Tracking of correct/incorrect moves
- Performance statistics

## Technologies Used

- C++ Programming Language
- SDL2 Library for graphics and multimedia
- Object-Oriented Programming concepts:
  - Classes and objects
  - Inheritance
  - Polymorphism
  - Encapsulation
  - Abstraction

## System Requirements

### Hardware Requirements
- Processor: 1 GHz or faster
- RAM: 512 MB minimum
- Graphics: Basic graphics card with support for SDL2
- Storage: 50 MB free space

### Software Requirements
- Operating System: Windows, Linux, or macOS
- C++ Compiler (GCC, Clang, or MSVC)
- SDL2 Library

## Installation and Setup

1. Clone the repository:
```bash
git clone https://github.com/Ronstha/chess-game.git
cd chess-game
```

2. Install SDL2 and dependencies:
   - **Ubuntu/Debian**:
     ```bash
     sudo apt-get install libsdl2-dev libsdl2-image-dev libsdl2-ttf-dev libsdl2-mixer-dev
     ```
   - **Fedora/RHEL**:
     ```bash
     sudo dnf install SDL2-devel SDL2_image-devel SDL2_ttf-devel SDL2_mixer-devel
     ```
   - **macOS** (using Homebrew):
     ```bash
     brew install sdl2 sdl2_image sdl2_ttf sdl2_mixer
     ```
   - **Windows**: Download and install the development libraries from the [SDL website](https://www.libsdl.org/download-2.0.php)

3. Compile the project:
```bash
make
```
   Or use the appropriate build system for your environment.

4. Run the game:
```bash
./chess
```

## Limitations

- Two players must use the same computer
- No option for undoing moves
- Game cannot be paused
- Fixed window size
- No AI opponent for single-player


## License

This project is available for educational purposes and is not licensed for commercial use.
