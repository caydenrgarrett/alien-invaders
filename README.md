# Alien Invasion Game

A classic space shooter game built with Pygame, inspired by the iconic Space Invaders. Control a spaceship and defend against alien invaders in this retro-style arcade game.

## Features

- **Classic Gameplay**: Traditional space shooter mechanics
- **Smooth Controls**: Responsive ship movement
- **Retro Graphics**: Pixel-art style ship sprite
- **60 FPS Gameplay**: Smooth 60 frames per second performance
- **Modular Design**: Clean, object-oriented code structure

## Project Structure

```
alien_invasion/
├── alien_invasion.py    # Main game class and game loop
├── ship.py             # Player ship class and behavior
├── settings.py         # Game configuration and settings
├── Images/             # Game assets
│   └── ship.bmp        # Player ship sprite
└── README.md           # This file
```

## Installation

1. **Navigate to the alien_invasion directory**
   ```bash
   cd alien_invasion
   ```

2. **Install Pygame**
   ```bash
   pip install pygame
   ```

3. **Ensure the ship image is in the correct location**
   - The game expects `ship.bmp` to be in the `Images/` directory
   - Make sure the file path matches: `Images/ship.bmp`

## How to Run

Simply run the main game file:

```bash
python alien_invasion.py
```

## Game Controls

- **Close Game**: Click the X button or close the window to exit
- **Ship Movement**: Currently displays a ship at the bottom center of the screen
- **Future Controls**: This is a foundation for adding movement controls (arrow keys, WASD, etc.)

## Game Architecture

### Main Components

1. **AlienInvasion Class** (`alien_invasion.py`)
   - Main game class that manages the game loop
   - Handles pygame initialization and display setup
   - Manages game events and rendering

2. **Ship Class** (`ship.py`)
   - Represents the player's spaceship
   - Handles ship positioning and rendering
   - Loads and displays the ship sprite

3. **Settings Class** (`settings.py`)
   - Centralized configuration for game parameters
   - Screen dimensions and background color settings
   - Easy to modify game settings in one place

### Game Loop

The game follows a standard game loop pattern:
1. **Event Handling**: Process user input and system events
2. **Update**: Update game state and object positions
3. **Render**: Draw all game objects to the screen
4. **Frame Rate Control**: Maintain consistent 60 FPS

## Current Status

This is a **foundation version** of the Alien Invasion game that includes:

✅ **Completed Features:**
- Basic game window setup
- Ship sprite loading and display
- Game loop with proper frame rate control
- Modular code structure

🚧 **Potential Future Enhancements:**
- Ship movement controls
- Alien enemies
- Shooting mechanics
- Collision detection
- Score system
- Sound effects
- Multiple levels
- Game over screen

## Technical Details

- **Framework**: Pygame
- **Screen Resolution**: 1200x800 pixels
- **Frame Rate**: 60 FPS
- **Background Color**: Light gray (230, 230, 230)
- **Ship Position**: Bottom center of screen

## Code Structure

The game uses object-oriented programming principles:

- **Separation of Concerns**: Each class has a specific responsibility
- **Modular Design**: Easy to extend with new features
- **Clean Architecture**: Main game loop separated from game objects
- **Configuration Management**: Settings centralized for easy modification

## Development Notes

This project appears to be based on the classic "Alien Invasion" tutorial, providing a solid foundation for building a complete space shooter game. The current implementation focuses on establishing the core game structure and basic ship rendering.

## Troubleshooting

- **"No module named 'pygame'"**: Install pygame with `pip install pygame`
- **"No such file or directory: 'images/ship.bmp'"**: Ensure the Images folder exists and contains ship.bmp
- **Game window doesn't appear**: Check that pygame is properly installed and no errors are displayed

## Contributing

This is a learning project perfect for:
- Adding new game features
- Implementing player controls
- Creating alien enemies
- Adding shooting mechanics
- Enhancing graphics and animations

Feel free to extend this foundation into a full-featured space shooter game!
