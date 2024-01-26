# Tic Tac Toe Game

## Introduction

This repository contains a simple command-line implementation of the classic Tic Tac Toe game in Python. The game allows a user to play against a computer opponent.

## How to Play

1. Run the script: `python easy_install.exe`
2. Follow the on-screen instructions to make your moves.
3. The game board will be displayed after each move.
4. The winner or a tie will be announced at the end of the game.

## Rules

1. The game is played on a 3x3 grid.
2. Players take turns marking an empty cell with their symbol ('X' for the user, 'O' for the computer).
3. The first player to get three of their symbols in a row (horizontally, vertically, or diagonally) wins the game.
4. If the board is filled and no player has won, the game is a tie.

## Functions

- **insertLetter(letter, pos):** Inserts the specified letter ('X' or 'O') at the given position on the board.
- **spaceIsFree(pos):** Returns `True` if the specified position on the board is empty; otherwise, returns `False`.
- **printBoard(board):** Prints the current state of the Tic Tac Toe board.
- **isBoardFull(board):** Returns `True` if the board is full; otherwise, returns `False`.
- **isWinner(board, letter):** Returns `True` if the specified player (with the given letter) has won the game; otherwise, returns `False`.
- **userMove():** Handles the user's move, taking input for the position and updating the board.
- **compMove():** Generates the computer's move based on a simple set of rules.
- **selectRandom(list_):** Returns a random element from the provided list.
- **main():** The main game loop that orchestrates the gameplay.

## Playing Again

After each game, the user is prompted to play again. Enter 'Y' to start a new game or 'N' to exit the program.

## Getting Started

1. Clone this repository: `git clone https://github.com/Shahrayar123/Python-Projects/tree/master/Tic-Tac-Toe`
2. Navigate to the project directory: `cd tic-tac-toe`
3. Run the game: `python tic_tac_toe.py`

## Contributing

Feel free to contribute to this project by suggesting improvements or reporting issues. Create a pull request or open an issue to get started.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

Thanks to OpenAI for providing the foundation for this project through the GPT-3.5 model.

Have fun playing Tic Tac Toe!
