# Zombie Game in Python

This project is a 3D first-person Zombie Game built using Python and Pygame, implementing raycasting for rendering a 3D environment. The game features a player navigating through a maze, with walls textured and rendered using the raycasting algorithm. The project files and resources include code for player movement, map creation, object rendering, and wall textures.

## Features
- 3D rendering using the Raycasting technique
- First-person player controls with mouse and keyboard
- Dynamic wall textures and interactive movement through a maze

## Prerequisites
To run the game, you'll need:
- Python 3.x
- Pygame library

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo-name/zombie-game.git
   cd zombie-game
   ```

2. Install the required Python dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Ensure that the following directory structure exists in the `resources` folder for textures:

   ```
   resources/
       └── textures/
           ├── 1.jpeg
           ├── 2.jpeg
           ├── 4.jpg
           ├── 5.jpg
           └── 6.jpg
       └── texture/
           └── sky.jpg
   ```

4. Run the game:
   ```bash
   python main.py
   ```

## Controls
- **W**: Move forward
- **S**: Move backward
- **A**: Strafe left
- **D**: Strafe right
- **Mouse Movement**: Rotate the player's view
- **Mouse Sensitivity**: Adjusted for more realistic control

## Files Overview
- `main.py`: Entry point for the game.
- `map.py`: Handles map creation and rendering of the world map.
- `player.py`: Handles the player's movement and view.
- `object_renderer.py`: Manages rendering of the game objects such as walls, sky, and other textures.
- `ray_casting.py`: Contains the raycasting logic for rendering the walls.
- `settings.py`: Stores game settings like resolution, player movement speed, field of view, and texture sizes.

## Resources
The game uses textures for the walls and sky. These textures are stored in the `resources/textures/` folder. You'll need to make sure the textures are in the correct directory as specified above.

## License
This project is for educational purposes and is open source under the MIT License.

## Author
Tathagata Sau
## Contact
[tathagatasu321@gmail.com]
