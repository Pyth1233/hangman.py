# Hangman Game

A simple Python implementation of the classic Hangman game. The objective is to guess the hidden word by suggesting letters within a certain number of attempts.

## Features

- Randomly selects a word for the player to guess.
- Tracks the number of incorrect attempts.
- Displays a visual representation of the hangman state as attempts are made.
- Allows for continuous play after a game finishes.
- Keeps track of correct and incorrect guesses.

## Requirements

- Python 3.x

## Installation

1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/yourusername/hangman-game.git
    ```

2. Navigate to the project directory:
    ```bash
    cd hangman-game
    ```

3. Run the game:
    ```bash
    python hangman.py
    ```

## How to Play

1. The game will display a word with blank spaces, representing the letters of the word.
2. The player is prompted to guess a letter.
3. After each guess, the game will:
   - Reveal correct letters in their respective positions.
   - Increase the hangman state for incorrect guesses.
4. The game ends when either:
   - The player guesses the word correctly.
   - The player runs out of attempts.

## Game Flow

1. A word is randomly chosen from a predefined list.
2. The player guesses letters, and the game keeps track of incorrect guesses.
3. The visual of the hangman is updated with each wrong guess.
4. The player wins if they guess all letters correctly before running out of attempts.
5. The player loses if the hangman is fully drawn (typically 6 or 7 wrong guesses).
6. After the game ends, the player can choose to play again.

## Example

