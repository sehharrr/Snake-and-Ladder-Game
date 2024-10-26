
# Snake and Ladder Game 

## Project Description

This project implements the classic **Snake and Ladder** game in C++ for two players. It is a simple, turn-based game played on a board with numbered squares ranging from 1 to 100. The players roll a die to move across the board, climbing ladders to advance more quickly and avoiding snakes that send them back down the board. The first player to reach square 100 wins.

## Table of Contents
- [Features](#features)
- [How to Play](#how-to-play)
- [Running the Game](#running-the-game)
- [Code Structure](#code-structure)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)


## Features

- **Two-player mode**: Both players take turns rolling the dice.
- **Board setup**: Ladders and snakes are placed at random positions.
- **Automatic dice roll**: Simulated dice rolling with random number generation.
- **Game logic**: Players climb ladders and avoid snakes while moving toward square 100.
- **Win detection**: The game announces the winner once a player reaches the final square.

## How to Play

1. Each player rolls a die and moves forward by the number rolled.
2. If a player lands on the bottom of a ladder, they move up to the top of the ladder.
3. If a player lands on the head of a snake, they slide down to the tail.
4. The first player to reach square 100 exactly wins the game.

### Board Layout

- The board is numbered from 1 to 100.
- Random ladders and snakes are placed on the board:
  - **Ladders**: Moving up (e.g., from 3 to 22).
  - **Snakes**: Moving down (e.g., from 17 to 7).



## Running the Game

1. Once you run the game, both players will take turns rolling the dice.
2. The game will display the board after every move and indicate if a player climbs a ladder or encounters a snake.
3. The game ends when one player reaches exactly 100, and the winner is announced.

### Example Gameplay Output:
```
Player 1 rolls a 4
Player 1 moves to 14
Player 1 climbs a ladder to 29
Player 2 rolls a 5
Player 2 moves to 5
...
Player 1 wins by reaching square 100!
```

## Code Structure

The code consists of the following components:

- **Game Board**: Contains the logic for placing snakes and ladders on the board.
- **Player Class**: Manages player positions and turns.
- **Dice Roll Simulation**: Uses random number generation to simulate dice rolls.
- **Game Logic**: Handles the main game loop, including win conditions, ladder climbing, and snake encounters.

## Future Enhancements

Here are some potential features and improvements:

- **Single-player mode**: Add a computer opponent with basic AI.
- **Graphical User Interface (GUI)**: Implement a GUI version using libraries like **SFML** or **Qt** for a visual representation of the board.
- **Configurable Snakes and Ladders**: Allow the user to customize the number and positions of snakes and ladders.
- **Multiplayer mode**: Add more than two players for a more competitive game.

## Contributing

Contributions are welcome! Here's how you can contribute:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-branch
   ```
3. Make your changes and commit:
   ```bash
   git commit -m "Add feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-branch
   ```
