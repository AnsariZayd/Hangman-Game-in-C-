# Hangman Game in C++

## Overview
This project is a console-based Hangman game written in C++. The objective of the game is to guess the name of a randomly selected month, one letter at a time, before the player runs out of chances.

## Features
- **Random month selection**: The game randomly picks a month name from a predefined list.
- **Player interaction**: The player is prompted to guess letters with feedback provided for correct or incorrect guesses.
- **Life system**: Players start with 3 lives and lose one for each incorrect guess.
- **Dynamic hangman visual**: A hangman figure is updated based on the player's progress in the game.
- **Winning and losing conditions**: Players win by guessing the full month name and lose if they run out of lives.

## Game Rules
- You have 3 chances to guess the correct letters of a randomly selected month.
- Each correct guess reveals the corresponding letters.
- Incorrect guesses reduce your remaining lives.
- The game ends when you guess the full month or run out of lives.

## How to Play
1. Run the program.
2. A random month will be selected, and its name will be hidden.
3. Guess letters one by one.
4. If the letter is correct, it will be revealed in the month name.
5. If incorrect, you lose a life.
6. Win by guessing the entire month before your lives run out!

## How to Run
1. Clone the repository:
    ```bash
    git clone https://github.com/AnsariZayd/hangman-game.git
    ```
2. Compile the code using a C++ compiler:
    ```bash
    g++ -o hangman hangman.cpp
    ```
3. Run the game:
    ```bash
    ./hangman
    ```

## Dependencies
- Standard C++ libraries (`<bits/stdc++.h>`, `<ctime>`)

## Future Improvements
- Add support for difficulty levels.
- Implement more categories (e.g., country names, animals).
- Improve hangman visuals for better user experience.
