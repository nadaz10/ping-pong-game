# Ping Pong Game

## Overview

Ping Pong Game is a classic arcade game implemented in Python using the Pygame library. The game features single-player mode where the player competes against an AI opponent. The AI difficulty can be adjusted to provide a challenging experience for players of all skill levels.

## Features

- **Single-player Mode**: Play against an AI opponent.
- **Adjustable Difficulty**: Choose between easy, medium, and hard difficulty levels.
- **Pygame Library**: Utilizes Pygame for graphical and sound elements.
- **Simple Controls**: Easy-to-learn controls for an enjoyable gaming experience.
- **Score Tracking**: Keeps track of the score during the game.

## Installation

To set up the Ping Pong Game on your local machine, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/ping-pong-game.git
    ```

2. **Navigate to the project directory**:
    ```bash
    cd ping-pong-game
    ```

3. **Set up the project environment**:
    - Ensure you have Python installed (Python 3.6 or higher).
    - Install the Pygame library:
        ```bash
        pip install pygame
        ```

4. **Run the application**:
    ```bash
    python main.py
    ```

## Usage

### Controls

- **Player Paddle**:
  - **Up**: Press the "W" key.
  - **Down**: Press the "S" key.

### Main Menu

- **Start Game**: Begin a new game.
- **Difficulty Levels**:
  - **Easy**: AI moves slower, suitable for beginners.
  - **Medium**: AI has moderate speed and responsiveness.
  - **Hard**: AI is fast and challenging.

### Gameplay

- **Objective**: The goal is to score points by hitting the ball past the opponent's paddle.
- **Scoring**: Each time the ball passes the opponent's paddle, the player scores a point. The first player to reach 10 points wins the game.

## Code Structure

- **main.py**: Entry point of the game.
- **game.py**: Contains the game loop and main game logic.
- **paddle.py**: Defines the Paddle class for player and AI paddles.
- **ball.py**: Defines the Ball class for the game ball.
- **settings.py**: Contains game settings and constants.

## Classes and OOP Design

- **Paddle**: Represents the paddles controlled by the player and AI.
- **Ball**: Represents the game ball and its behavior.
- **Game**: Manages the game state, including the main game loop, event handling, and rendering.


