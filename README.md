# Hangman Game

This is a simple Hangman game implemented in Python. The game randomly selects a word from a predefined list of words, and the player has to guess the word by suggesting letters within a certain number of guesses.

## How to Play

1. Run the `Main.py` script.
2. The game will randomly select a word and display underscores representing each letter in the word.
3. Enter a letter to guess.
4. If the letter is in the word, it will be revealed in the correct position(s).
5. If the letter is not in the word, a part of the hangman will be drawn.
6. Continue guessing letters until you either guess the word correctly or the hangman is fully drawn.

## Files

- `Main.py`: The main script that runs the Hangman game.
- `wordslist.py`: (Optional) A separate file containing the list of words (not used in the current implementation).

## Code Overview

### `Main.py`

- `words`: A tuple containing a list of words to be used in the game.
- `hangman_art`: A dictionary representing the hangman drawing at different stages of the game.
- `display_man(wrong_guesses)`: Function to display the current state of the hangman.
- `display_hint(hint)`: Function to display the current hint with guessed letters.
- `display_answer(answer)`: Function to display the correct answer.
- `main()`: The main function that runs the game loop.

## How to Run

1. Ensure you have Python installed on your system.
2. Clone or download this repository.
3. Navigate to the directory containing `Main.py`.
4. Run the script using the command:
   ```sh
   python Main.py
