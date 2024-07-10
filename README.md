
# Snake Game

This is a simple implementation of the classic Snake game using Python and Pygame.

## Requirements

- Python 3.x
- Pygame

## Installation

1. Install Python 3.x from the [official website](https://www.python.org/).

2. Install Pygame using pip:

```
pip install pygame
```

## How to Run

1. Download the `snake_game.py` script.

2. Run the script using Python:

```
python snake_game.py
```

## Game Controls

- Use the arrow keys (Up, Down, Left, Right) to move the snake.
- Press `Q` to quit the game when you lose.
- Press `C` to play again when you lose.

## Game Features

- Keeps track of the highest score and saves it to a file named `high_score.txt`.
- Displays the current score and the highest score in the game window.

## Code Overview

- `our_snake(snake_block, snake_list)`: Draws the snake on the screen.
- `message(msg, color)`: Displays a message on the screen.
- `show_score(score, high_score)`: Displays the current score and high score on the screen.
- `get_high_score()`: Reads the high score from `high_score.txt`.
- `save_high_score(score)`: Saves the high score to `high_score.txt`.
- `gameLoop()`: Main game loop handling game logic, input, and rendering.

## Notes

- The snake moves in a grid defined by `snake_block` size.
- The snake's speed is defined by `snake_speed`.

Enjoy playing the game!
