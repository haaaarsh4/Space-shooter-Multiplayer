# Space Shooter Multiplayer

This is a simple two-player game implemented in Python using the Pygame library. The game features two spaceships, one controlled by the player on the left (Red spaceship) and the other by the player on the right (Yellow spaceship). The objective is to shoot the opponent's spaceship while avoiding getting hit.

## Prerequisites

Before running this game, make sure you have the following installed:

- Python 3 (https://www.python.org/downloads/)
- Pygame library (```pip install pygame```)

## How to Run

To run the game, follow these steps:

1. Clone or download the source code to your local machine.
2. Open a terminal or command prompt and navigate to the directory where the source code is located.
3. Run the following command:

   ```
   python first_game.py
   ```

4. The game window should open, and you can start playing.

## Controls

- Player 1 (Red spaceship):
  - Move left: Left arrow key
  - Move right: Right arrow key
  - Move up: Up arrow key
  - Move down: Down arrow key
  - Shoot: Right Ctrl key

- Player 2 (Yellow spaceship):
  - Move left: A key
  - Move right: D key
  - Move up: W key
  - Move down: S key
  - Shoot: Left Ctrl key

## Gameplay

- Each player starts with 10 health points.
- The spaceships can move in four directions: up, down, left, and right.
- Spaceships cannot cross the center boundary line.
- Press the shoot key (Right Ctrl for Player 1, Left Ctrl for Player 2) to fire bullets.
- Each player can have a maximum of 3 bullets on the screen at a time.
- If a bullet hits the opponent's spaceship, one point of health is deducted from the opponent.
- The game ends when one player's health reaches zero.
- The winner is displayed on the screen for 5 seconds before the game closes.

Enjoy playing the game!
