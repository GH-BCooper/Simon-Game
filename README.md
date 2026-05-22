# 🎮 Simon Game

A browser-based memory game inspired by the classic Simon Game.  
The game generates a random sequence of colors, and the player must repeat the pattern correctly to advance to higher levels.

---

## 🚀 Features

- Random color sequence generation
- Interactive button animations
- Sound effects for every button
- Increasing difficulty with each level
- Game over detection and restart functionality
- Keyboard-based game start

---

## 🎯 How to Play

1. Press any key to start the game
2. Watch the color sequence carefully
3. Repeat the exact pattern by clicking the buttons
4. Each new level adds another color to the sequence
5. One wrong click ends the game

---

## 🎨 Button Colors

- 🔴 Red
- 🔵 Blue
- 🟢 Green
- 🟡 Yellow

---

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- jQuery

---

## ⚙️ Game Logic

### Game Initialization
The game starts when the user presses any key.

### Sequence Generation
The `nextSequence()` function:
- Generates a random color
- Adds it to the game pattern
- Plays animation and sound
- Updates the level counter

### User Input Tracking
Whenever a button is clicked:
- The selected color is stored
- Sound and animation are triggered
- User input is checked against the original pattern

### Answer Validation
The `checkAnswer()` function:
- Compares user clicks with the generated sequence
- Advances to the next level if correct
- Ends the game if incorrect

### Game Over
On a wrong answer:
- A "wrong" sound is played
- Screen flashes with a game-over effect
- Restart message is displayed
- Game variables are reset

---

## 📁 Project Structure

```bash
Simon-Game/
│
├── index.html
├── styles.css
├── game.js
│
├── sounds/
│   ├── red.mp3
│   ├── blue.mp3
│   ├── green.mp3
│   ├── yellow.mp3
│   └── wrong.mp3
│
└── README.md


▶️ How to Run
Download or clone the repository
Open the project folder
Open index.html in your browser
Press any key to begin