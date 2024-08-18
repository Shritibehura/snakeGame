# Snake Game

This is a classic Snake game implemented using Pygame. The objective is to control the snake to eat apples, grow in size, and avoid collisions with itself or the screen edges.

## Features

- **Classic Snake Gameplay**: Navigate the snake using arrow keys to collect apples.
- **Dynamic Difficulty**: The game increases in difficulty as the snake grows longer.
- **Screen Wrapping**: The snake wraps around the edges of the screen, appearing on the opposite side.
- **Collision Detection**: Detects collisions between the snake and itself to end the game.
- **Score Tracking**: Keeps track of the score based on the number of apples eaten.
- **Game Timer**: Displays the elapsed time since the start of the game.
- **Apple Respawning**: Apples respawn in random positions after being eaten.
- **Game Over Screen**: Provides options to restart or exit the game upon losing.

## Requirements

- Python 3.x
- Pygame library

## Installation

1. **Clone the repository**:

    ```bash
    git clone https://github.com/Shritibehura/snakeGame.git
    ```

2. **Navigate to the project directory**:

    ```bash
    cd snake-game
    ```

3. **Install dependencies**:

    ```bash
    pip install pygame
    ```

## Running the Game

To start the game, run the following command:

```bash
python main.py
