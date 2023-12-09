# Hangman Game in Python

## Overview

This Python script is a simple implementation of the classic word-guessing game, Hangman. The game selects a random word from a predefined list, and the player attempts to guess it one letter at a time. Each incorrect guess results in a part of the hangman being drawn, and the game continues until the player either guesses the word correctly or runs out of lives.

## Features

- Random word selection from a list.
- Player can guess one letter at a time.
- Visual representation of the hangman (requires `hangman_art` module).
- Keeps track of the player's remaining lives.
- Reveals letters in the word as they are correctly guessed.
- Notifies the player of already guessed letters.
- Declares a win or loss based on the player's guesses.

## Requirements

- Python 3.x
- `hangman_art` module (for displaying hangman graphics and logo).
- `hangman_words` module (for the list of words).

## Usage

1. Ensure the required modules (`hangman_art`, `hangman_words`) are in the same directory as the script.
2. Run the script using Python.
3. The game will display a series of underscores representing the letters of a randomly chosen word.
4. The player inputs guesses for letters in the word.
5. The game provides feedback on correct and incorrect guesses and updates the display and hangman graphic accordingly.
6. The game ends when the player either guesses the word correctly or runs out of lives.

## Example Output

```
  +---+
  |   |
  O   |
 /|\  |
 / \  |
      |
=========
```

## Note

This script does not handle input validation (e.g., checking for single letters, non-alphabetic characters), so it assumes valid input from the user.

---

Enjoy the game and try to guess the word before your hangman is fully drawn!