# README.md

---

# Turtle Crossing Game

Welcome to the Turtle Crossing Game repository. This game is a modern rendition of the classic Frogger game, where you control a turtle attempting to cross a busy street. Written in Python, this game uses the turtle graphics module to create a simple but engaging graphical interface.

![Game Screenshot](./screenshot.png)

## Game Files

This repository includes the following Python files:

1. `main.py`: This is the entry point of the game. It combines all other modules and runs the game.

2. `player.py`: This file contains the `Player` class which is responsible for creating the player's turtle and controlling its movement.

3. `car_manager.py`: This file contains the `CarManager` class. It is responsible for creating cars, controlling their speed and movement, and checking for collisions with the player.

4. `scoreboard.py`: This file contains the `Scoreboard` class, which is responsible for displaying and updating the game score and level.

## How to Play

- Clone this repository to your local machine.
- Navigate to the directory of the game.
- Run `python main.py` to start the game.
- Use the 'Up' arrow key to move the turtle forward.
- The goal is to reach the top of the screen. Each time the turtle reaches the top, it moves to the next level and the game speed increases.
- Avoid getting hit by cars. If the turtle is hit, the game ends.

## Prerequisites

- This game requires Python 3. Python can be downloaded from [here](https://www.python.org/downloads/).
- The game uses the `turtle` module for graphics, which comes pre-installed with Python.

## Gameplay Tips

- Be patient! Rushing across can result in running into a car.
- Observe the patterns. Cars come in patterns, and if you observe them, you can find the best time to cross.
- Every new level will bring more speed and cars, be ready!

## Contributing

- We love to have your help to make this project better. All contributions are welcome!
- For major changes, please open an issue first to discuss what you would like to change.
- Please make sure to update tests as appropriate.

## License

- This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/).

---

We hope you enjoy playing the Turtle Crossing Game as much as we enjoyed building it. Your satisfaction is our priority. Happy gaming!
