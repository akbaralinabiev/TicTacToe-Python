# Tic-Tac-Toe Game

This is a command-line implementation of the classic Tic-Tac-Toe game. The game allows two players to take turns and compete against each other until there is a winner or a tie.

## Features

- Play against another human player or a random computer player.
- The game displays the current state of the board after each move.

## How to Play

1. Run the `game.py` file in your terminal using Python 3: 

3. The game will prompt you to enter moves for each player in the command line.

3. Player X starts the game. When prompted, enter the desired move as a number from 0 to 8, corresponding to the board positions:


4. The game will continue until there is a winner or a tie.

5. Enjoy playing Tic-Tac-Toe!

## Customization

- You can customize the game by creating different types of players. Currently, the game supports a Human Player `HumanPlayer` and a Random Computer Player `RandomComputerPlayer`.
- To create a new player, create a new class that extends the `Player` class and implement the `get_move` method.


- In the `play` function of `gam.py`, you can modify the players used for the game.

## File Structure

The repository contains the following files:

- `gam.py`: The main Python script that implements the Tic-Tac-Toe game logic.
- `player.py`: A module containing the player classes used in the game.
- `README.md`: This file, providing information about the game and instructions.

## Dependencies

The game has been implemented using Python 3. No additional libraries or dependencies are required.

## License
Author: Akbarali Nabiev
This project is licensed under the MIT License. Feel free to use and modify it according to your needs.
