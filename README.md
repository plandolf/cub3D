# cub3D

## Introduction

cub3D is inspired by the classic game Wolfenstein 3D, known as the first First-Person Shooter (FPS). This project is designed to introduce you to the fundamental principles of ray-casting in a graphical environment using the miniLibX library.

## Features

- **Ray-Casting**: Implements ray-casting to generate a 3D perspective from a 2D map.
- **Dynamic View**: Allows for real-time movement and exploration within the maze.
- **Texture Management**: Walls have different textures based on their orientation (North, South, East, West).
- **Control System**: Uses keyboard controls for navigation and viewing direction within the maze.
- **Window Management**: Handles window events like minimizing and closing smoothly.
- **Map Parsing**: The program reads and validates the map configuration from a `.cub` file.

## Getting Started

### Prerequisites

- A C compiler (GCC recommended)
- miniLibX library installed (available on Unix systems)

### Installation

1) git clone [repository-url] cub3D
2) cd cub3D
3) make all


## Usage

To run the program, you must provide a map file in `.cub` format as an argument:

./cub3D path_to_map.cub

Ensure your map file is correctly formatted according to the specifications provided in the project documentation.

## Controls

- **Arrow Keys**: Look left and right.
- **WASD**: Move forward, left, back, and right.
- **ESC**: Exit the game.
