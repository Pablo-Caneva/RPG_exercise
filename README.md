# RPG exercise - Dragon Repeller

Welcome to **Dragon Repeller**, a simple RPG game where you must defeat a dragon to free the townspeople. The game is designed using basic HTML, CSS, and JavaScript. The player can explore different locations, fight monsters, and upgrade their character's weapons and stats.

## Table of Contents

- [Features](#features)
- [Game Mechanics](#game-mechanics)
- [Installation](#installation)
- [How to Play](#how-to-play)
- [Code Structure](#code-structure)
- [License](#license)

## Features

- **Interactive UI:** Use buttons to navigate through the game and make decisions.
- **Multiple Locations:** Explore the town square, store, and cave.
- **Combat System:** Fight monsters with different levels and health points.
- **Inventory Management:** Upgrade your weapons and manage your inventory.
- **Random Events:** Experience random outcomes in battles and mini-games.
- **Win/Lose Scenarios:** Defeat the dragon to win, or lose all your health to restart the game.

## Game Mechanics

- **Experience Points (XP):** Gain XP by defeating monsters. XP affects the power of your attacks.
- **Health:** Start with 100 health points. If health drops to 0, you lose the game.
- **Gold:** Earn gold by defeating monsters and use it to buy health or weapons.
- **Weapons:** Start with a stick and upgrade to more powerful weapons like a sword.

## Installation

1. Clone the repository or download the project files.
2. Open the `index.html` file in your web browser to start the game.

## How to Play

1. **Explore Locations:** Use the buttons to navigate to different locations such as the town square, store, or cave.
2. **Fight Monsters:** Enter the cave to fight monsters. Choose to attack, dodge, or run.
3. **Buy Upgrades:** Visit the store to buy health or weapons using the gold you earn.
4. **Defeat the Dragon:** Fight the dragon in the town square to win the game.
5. **Manage Inventory:** Upgrade your weapons as you progress, but be careful—your weapons can break!

## Code Structure

- **HTML:** The structure of the game, including stats, controls, and game text.
- **CSS:** Styles for the game's layout, buttons, and text.
- **JavaScript:** The core game logic, including location updates, combat, inventory management, and random events.

### Key JavaScript Functions

- `goTown()`, `goStore()`, `goCave()`: Navigate between locations.
- `buyHealth()`, `buyWeapon()`, `sellWeapon()`: Manage health and inventory.
- `fightSlime()`, `fightBeast()`, `fightDragon()`: Start battles with monsters.
- `attack()`, `dodge()`, `lose()`, `winGame()`: Core combat and game progression logic.
- `restart()`: Restart the game after losing or winning.

## License

This project is licensed under the MIT License. Feel free to use, modify, and distribute the code as you like.
