**Project Title:** Battleship Game in Python

**Description:**

This repository contains a Python implementation of the classic Battleship game, designed as a school project. The game is played between two players who take turns guessing the locations of each other's ships on a grid. The objective is to sink all of the opponent's ships before they can sink yours.

**Features:**
- **Interactive Gameplay:** Players can place their ships on a grid and take turns attacking each other's boards.
- **Ship Placement:** Ships can be placed either horizontally or vertically on the board.
- **Attack Mechanism:** Players can attack specific coordinates on the opponent's board, with hits and misses being marked accordingly.
- **Game Over Detection:** The game automatically detects when all ships of a player have been sunk, declaring the other player as the winner.
- **High Score Tracking:** The game records the number of guesses each player takes to win and displays the high score after each game.

**Files Included:**
1. **`board.py`:** Contains the `Board` class, which manages the game grid, ship placement, and attack logic.
2. **`ship.py`:** Contains the `Ship` class, which represents a ship with attributes like name, size, and hit count.
3. **`player.py`:** Contains the `Player` class, which handles player actions such as placing ships and attacking the opponent's board.
4. **`game.py`:** Contains the `Game` class, which manages the overall game flow, including player turns, game over conditions, and high score tracking.
5. **`testing.py`:** Contains unit tests to verify the functionality of the game components.

**How to Play:**
1. Run the `game.py` script to start the game.
2. Enter the names of the two players.
3. Players take turns placing their ships on their respective boards.
4. Once all ships are placed, players take turns attacking each other's boards by entering coordinates.
5. The game ends when all ships of one player are sunk, and the winner is announced.

**Usage:**
This project is ideal for educational purposes, demonstrating concepts such as object-oriented programming, grid-based game logic, and user interaction in Python. It can be used as a base for further enhancements or as a learning tool for students.

**Contributing:**
Feel free to fork this repository and contribute by adding new features, improving the code, or fixing bugs. Pull requests are welcome!

**License:**
This project is open-source and available under the MIT License. See the LICENSE file for more details.
