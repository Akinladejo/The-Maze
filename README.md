# Maze-Project-Landing-Page
The Maze

**The Maze** is a 3D Maze game that uses ray casting to render a 2D map into a 3D navigable world!

## Table of Contents
1. [About The Maze](#about-the-maze)
2. [Development](#development)
3. [About SDL2](#about-sdl2)
4. [Getting Started](#getting-started)
5. [How to Play](#how-to-play)
6. [Screenshots](#screenshots)
7. [Contributing](#contributing)
8. [License](#license)

## About The Maze
The Maze is a 3D maze exploration game where the player navigates through a labyrinthine environment. The game uses ray casting techniques to transform a 2D map into an immersive 3D world, providing a first-person perspective experience.

## Development
The Maze was developed in C using the SDL2 library. The development environment included:
- **Operating System**: Ubuntu 14.04 LTS
- **Compiler**: gcc (Ubuntu 4.8.4-2ubuntu1~14.04) 4.8.4

## About SDL2
[Simple DirectMedia Layer (SDL2)](https://www.libsdl.org/) is a cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL and Direct3D. It is used by video playback software, emulators, and popular games, including Valve's award-winning catalog and many Humble Bundle games.

## Getting Started
### Prerequisites
To run The Maze, you need:
- GCC compiler
- SDL2 library

### Installation
1. **Clone the repository**:
    ```sh
    git clone https://github.com/0sei531/The-Maze.git
    cd The-Maze
    ```
2. **Install SDL2**:
    ```sh
    sudo apt-get install libsdl2-dev
    ```
3. **Compile the game**:
    ```sh
    gcc -o maze maze.c -lSDL2
    ```
4. **Run the game**:
    ```sh
    ./maze
    ```

## How to Play
- Use the arrow keys to navigate through the maze.
- The objective is to find the exit point of the maze.
