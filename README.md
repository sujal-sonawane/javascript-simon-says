# JavaScript Simon Says Game

## Overview

A browser-based Simon Says memory game developed using HTML5, CSS3, and JavaScript. The project recreates the basic Simon Says game concept where the player follows an increasingly longer sequence of colored buttons and attempts to repeat the sequence correctly.

This project was created to practice JavaScript fundamentals, DOM manipulation, event handling, arrays, conditional logic, random number generation, and basic game logic.

---

## Features

- Interactive Simon Says memory game
- Randomly generated color sequences
- Increasing difficulty as the level progresses
- Keyboard-based game start
- Mouse-based button interaction
- Visual button flash effects
- User sequence tracking
- Game-over detection
- Score/level display
- Restart functionality after game over

---

## Technologies Used

- HTML5
- CSS3
- JavaScript

---

## JavaScript Concepts Practiced

- Variables using `let`
- Arrays
- Functions
- `if` / `else` conditional statements
- `for...of` loops
- `Math.random()`
- `Math.floor()`
- DOM selection using `querySelector()` and `querySelectorAll()`
- Event listeners using `addEventListener()`
- Keyboard events
- Mouse click events
- `classList.add()` and `classList.remove()`
- `getAttribute()`
- `setTimeout()`
- Game state management
- Comparing arrays and user input
- Dynamic HTML content updates

---

## Game Logic

The game follows these basic steps:

1. The player starts the game using the keyboard.
2. A random color is selected and added to the game sequence.
3. The selected button flashes to show the player the sequence.
4. The player clicks the buttons in the same order.
5. Each user input is compared with the generated sequence.
6. If the complete sequence is correct, the game moves to the next level.
7. A new color is added to the sequence at each level.
8. If the player selects the wrong button, the game ends and the final level is displayed.

---

## Project Structure

```text
javascript-simon-says/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

---

## How to Run

### Method 1: Open Directly

1. Clone or download this repository.
2. Open the project folder.
3. Double-click `index.html`.
4. The game will open in your default web browser.

### Method 2: Using VS Code

1. Open the project folder in Visual Studio Code.
2. Open `index.html`.
3. Right-click the file.
4. Select **Open with Live Server** if the Live Server extension is installed.

---

## How to Play

1. Open the game in your browser.
2. Press a keyboard key to start.
3. Watch the color sequence carefully.
4. Click the buttons in the same order.
5. Each successful round increases the level.
6. Continue until you make a mistake.
7. Start again after game over to try for a higher score.

---

## Learning Outcomes

Through this project, I practiced:

- Understanding JavaScript program flow
- Manipulating HTML elements through the DOM
- Handling user interactions with event listeners
- Working with arrays and loops
- Generating random values
- Managing game state
- Comparing user input with generated data
- Creating visual feedback using CSS classes
- Using timers with `setTimeout()`
- Building a simple interactive browser game

---

## Future Improvements

The game can be further improved by adding:

- High-score tracking using Local Storage
- Difficulty levels
- Sound effects for each button
- Start and restart buttons
- Mobile-friendly responsive design
- Better game animations
- Pause functionality
- Score history

---

## Author

**Sujal Sonawane**

Electronics & Telecommunication Engineering Student

### GitHub

https://github.com/sujal-sonawane

### LinkedIn

https://www.linkedin.com/in/sujal-sonawane-bb5bb3320/

---

## License

This project is created for educational and learning purposes.
