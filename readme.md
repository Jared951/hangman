# Hangman Game Readme

This README provides an overview of the Hangman game implemented in React. The game consists of a simple hangman word guessing game where players guess letters to complete a hidden word. The game interface includes a drawing of the hangman, the word to guess, and a keyboard for selecting letters. Players can win by guessing the word correctly or lose if they make too many incorrect guesses.

## Table of Contents
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Gameplay](#gameplay)
- [Customization](#customization)
- [License](#license)

## Project Structure

The Hangman game is structured as follows:

- `HangmanDrawing.js`: A component that displays the hangman drawing based on the number of incorrect guesses.
- `HangmanWord.js`: A component that displays the word to guess with hidden letters.
- `Keyboard.js`: A component that provides a virtual keyboard for selecting letters.
- `wordList.json`: A JSON file containing a list of words that can be used for guessing.

## Getting Started

To run the Hangman game locally, follow these steps:

1. Clone the repository or download the source code.
2. Ensure you have [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/) installed on your machine.

## Installation

3. Open your terminal and navigate to the project directory.
4. Install the project dependencies by running the following command: npm install and then npm start
5. Open a web browser and go to http://localhost:3000 to play the Hangman game.

## Gameplay

The Hangman game is a classic word guessing game with the following rules:

- The game selects a random word from the word list.
- Players can guess letters by clicking on the virtual keyboard or by typing them on their physical keyboard.
- Incorrect guesses are counted, and the hangman drawing progresses with each wrong guess.
- The game is lost if there are six or more incorrect guesses (the hangman is fully drawn).
- The game is won if the player correctly guesses all the letters in the word.
- Players can restart the game by pressing the "Enter" key.

## Customization

You can customize the Hangman game by making changes to the code or the word list:

- Add more words to the wordList.json file to increase the variety of words that can be guessed.
- Modify the game's appearance by adjusting the CSS styles in the App component.