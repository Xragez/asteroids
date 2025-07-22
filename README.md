# Asteroids

A classic Asteroids arcade game clone built with Python and Pygame.

![Asteroids Game](https://raw.githubusercontent.com/pygame/pygame/main/docs/reST/_static/pygame_logo.svg)

## Description

This is a modern implementation of the classic Asteroids arcade game from 1979. Control a spaceship in space, shoot asteroids, and avoid collisions. The game features:

## Controls

- **W**: Thrust forward
- **S**: Thrust backward
- **A**: Rotate counterclockwise
- **D**: Rotate clockwise
- **SPACE**: Shoot

## Installation

### Dependencies

- Python 3.10 or higher
- Pygame 2.6.1

### Setup

Clone this repository:
```bash
git clone https://github.com/Xragez/asteroids
cd asteroids
```
(Optional) Create and activate a uv virtual environment:

```bash
uv venv
source .venv/bin/activate
```
[uv documentation](https://github.com/astral-sh/uv)

## Running the Game
To run the game, execute the main.py script:
```bash
uv run main.py
```

## Game Mechanics

- The player controls a triangular spaceship in the center of the screen
- Asteroids spawn from the edges of the screen and move in random directions
- When shot, larger asteroids split into smaller ones
- The game ends if the player's ship collides with an asteroid