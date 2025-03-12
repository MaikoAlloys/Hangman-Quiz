# Hangman Quiz

## Overview
Hangman Quiz is a simple text-based word-guessing game implemented in Python. The game randomly selects a word from a predefined list, and the player has a limited number of attempts to guess the word by guessing individual letters.

## Features
- Randomly selects a word from a predefined list.
- Displays the word as underscores to represent unguessed letters.
- Allows the player to input letter guesses.
- Provides feedback on correct and incorrect guesses.
- Limits the number of incorrect attempts to 8.
- Ends with either a win or loss message.

## How to Play
1. Run the Python script.
2. A word will be randomly chosen, and you must guess letters one by one.
3. Correct guesses will reveal the letters in the word.
4. Incorrect guesses will reduce the number of remaining attempts.
5. If you guess all letters correctly before running out of attempts, you win.
6. If you use up all attempts without guessing the word, you lose.

## Prerequisites
- Python 3.x installed on your system.

## Installation & Usage
1. Clone this repository:
   ```sh
   git clone https://github.com/MaikoAlloys/Hangman-Quiz.git
   ```
2. Navigate to the project directory:
   ```sh
   cd Hangman-Quiz
   ```
3. Run the script:
   ```sh
   python hangman.py
   ```

## Future Improvements
- Implement input validation to handle non-alphabet characters.
- Track and prevent repeated incorrect guesses.
- Add a scoring system.
- Improve user interface (e.g., GUI version with Tkinter or Pygame).

## License
This project is open-source and available under the MIT License.

## Contributing
Feel free to fork this repository and submit pull requests for enhancements or bug fixes.

## Author
[MaikoAlloys](https://github.com/MaikoAlloys)

