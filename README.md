# Time Capsule Snake Game (Python Turtle)

This project is a simple implementation of the classic Snake game, built using Python’s `turtle` module. Originally developed as a learning project some time ago, it’s now being shared as a time capsule — a preserved snapshot of an earlier phase in my programming journey.

The game features score tracking, food generation, wall collision, and tail collision logic, all created using object-oriented principles and Python's standard library.

## Gameplay Overview

- Control the snake using the arrow keys: **Up**, **Down**, **Left**, **Right**.
- Eat the blue food to grow longer and increase your score.
- Avoid running into the walls or your own tail — or the game resets.
- Your highest score is saved between sessions in a local `data.txt` file.

## Technologies Used

- Python 3
- Built-in `turtle` graphics module
- Basic file I/O for high score tracking
- Object-Oriented Programming (OOP)

## File Overview

- `main.py` – Main game loop and screen setup.
- `snake.py` – Handles snake creation, movement, growth, and reset logic.
- `food.py` – Spawns and repositions food items.
- `scoreboard.py` – Displays and updates score, manages high score file.

## How to Clone and Run

### Clone the Repository

If you're pulling this from GitHub, you can clone it like so:

```bash
git clone https://github.com/ajs2583/time-capsule-snake-game.git
cd time-capsule-snake-game
