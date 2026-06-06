# Wordle Game - A Web-Based Word Puzzle

This is a simple web-based game inspired by the popular Wordle puzzle, challenging you to guess a five-letter word in six attempts. It's designed to be intuitive and provides immediate feedback to help you hone your guesses.

## Live Demo 
VISIT LIVE WEBSITE:https://hareeshwar-chowdary-mullapudi.github.io/Wordle/

## Built With

* **HTML5**: For structuring the game board, keyboard, and overall page layout.
* **CSS3**: For all the visual styling, including tile feedback (green, yellow, gray), keyboard appearance, and responsive design.
* **JavaScript**: The core logic engine, handling user input, checking guesses, managing game state (wins/losses), and providing dynamic visual updates.
* `wordlist.js` (Assumed): A separate JavaScript file likely containing the comprehensive list of valid words for the game.

## How to Play

1.  **Guess the Word**: Type a five-letter word using your physical keyboard or the on-screen virtual keyboard.
2.  **Submit Your Guess**: Press "Enter" (or click the virtual "Enter" key) to submit your chosen word.
3.  **Get Feedback**:
    * **Green**: The letter is correct and in the right position.
    * **Yellow**: The letter is in the word but in the wrong position.
    * **Gray**: The letter is not in the word at all.
4.  **Keep Guessing**: Use the color-coded feedback to refine your subsequent guesses. You have a total of six attempts.
5.  **Win or Lose**: If you correctly guess the word within six tries, you win! Otherwise, the correct word will be revealed at the end of the game.

## Project Structure

* `index.html`: The main entry point, defining the overall structure and layout of the game.
* `style.css`: Contains all the CSS rules to visually style the game board, keyboard, and provide tile feedback.
* `hari.js` (or similar): Houses the core JavaScript game logic, managing user interaction, guess validation, and game state.
* `wordlist.js` (Assumed): A dedicated file holding the array of valid five-letter words for the game.

## Things I've Mastered with this Project

* **Event Handling**: Effectively capturing and processing user input from both physical and virtual keyboards.
* **DOM Manipulation**: Dynamically updating the game board and keyboard visuals based on user actions and game state.
* **Algorithmic Logic**: Implementing the core Wordle-like feedback mechanism (green, yellow, gray) for guess evaluation.
* **State Management**: Tracking the game's progress, including attempts remaining, current guess, and win/loss conditions.
* **Interactive UI Development**: Creating a responsive and engaging user interface purely with HTML, CSS, and JavaScript.
