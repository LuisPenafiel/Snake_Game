# Snake Game with Pygame

This is a simple Snake game implemented using the Pygame library in Python. The game features a snake that grows in length as it eats food, and the player must avoid colliding with the walls or itself.

## Features

- **Snake Movement**: The snake moves in four directions (up, down, left, right) based on player input.
- **Food Consumption**: The snake grows longer each time it eats a piece of food.
- **Grid-Based Movement**: The game is played on a grid, and the snake wraps around the screen edges.
- **Self-Collision Detection**: The game ends if the snake collides with itself.
- **Random Food Placement**: Food is randomly placed on the grid, avoiding the snake's body.

## Requirements

- Python 3.x
- Pygame library

## Installation

1. **Install Python**: Make sure you have Python 3.x installed on your system. You can download it from [python.org](https://www.python.org/).

2. **Install Pygame**: You can install Pygame using pip. Run the following command in your terminal or command prompt:

   ```bash
   pip install pygame
   ```

3. **Download the Game**: Clone or download this repository to your local machine.

## How to Run

1. Navigate to the directory where the `snake_pi.py` file is located.

2. Run the game using Python:

   ```bash
   python snake_pi.py
   ```

3. Use the arrow keys to control the snake:
   - **Up Arrow**: Move up
   - **Down Arrow**: Move down
   - **Left Arrow**: Move left
   - **Right Arrow**: Move right

4. The game will end if the snake collides with itself. You can close the game window to exit.

## Code Structure

- **Cube Class**: Represents each segment of the snake and the food. Handles drawing and position updates.
- **Snake Class**: Manages the snake's body, movement, and growth. Handles turning and collision detection.
- **Main Function**: Initializes the game, handles the game loop, and manages events like quitting the game.

## Customization

- **Grid Size**: You can change the number of rows in the grid by modifying the `rows` variable in the `main` function.
- **Window Size**: Adjust the `width` variable in the `main` function to change the size of the game window.
- **Snake Color**: Modify the `color` parameter in the `Snake` class initialization to change the snake's color.
- **Food Color**: Change the color of the food by modifying the `pygame.draw.rect` call in the `redrawWindow` function.

## Contributing

Feel free to fork this repository and submit pull requests with improvements or new features. If you find any bugs or have suggestions, please open an issue.

## License

This project is open-source and available under the MIT License. See the LICENSE file for more details.

## Acknowledgments

- Thanks to the Pygame community for providing excellent documentation and resources.
- Inspired by classic Snake games.

Enjoy the game! 🐍