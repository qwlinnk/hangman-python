# Hangman — Python

A console-based Hangman game written in Python.

The player must guess a randomly selected Russian word by entering one letter at a time. The game displays the current word, tracks incorrect guesses, and updates an ASCII drawing of the hangman.

## Features

- Random word selection from a built-in collection of Russian words
- Letter-by-letter guessing
- Automatic revealing of all occurrences of a correctly guessed letter
- Input validation
- Tracking incorrect guesses
- Repeated guesses do not count as additional mistakes
- ASCII hangman drawing that updates after incorrect guesses
- Win and loss detection
- Ability to start a new game without restarting the program

## How to Run

1. Make sure Python 3 is installed.
2. Clone or download this repository.
3. Open a terminal in the project directory.
4. Run the game:

   `python3 main.py`

No external libraries are required.

## How to Play

1. Enter `1` to start a new game or `2` to exit.
2. The computer randomly selects a Russian word.
3. Enter one Russian letter at a time.
4. Correct letters are revealed in the hidden word.
5. Incorrect guesses increase the mistake counter and update the hangman drawing.
6. You can make up to **5 mistakes**. The 6th incorrect guess ends the game.
7. Guess all the letters to win.
8. After the game ends, you can play again or exit.

## Project Structure

- `main.py` — game logic, word selection, input validation, and ASCII visualization

## Python Concepts Practiced

- Functions
- Loops and conditional statements
- Lists and sets
- String manipulation
- Working with user input
- Random number generation
- Basic input validation

## About

This is one of my early Python projects, created to practice programming fundamentals before moving on to Object-Oriented Programming.

The game runs entirely in the terminal.