# TicTacToe Game

A simple, interactive Tic Tac Toe game built with vanilla HTML, CSS, and JavaScript.

## Description

This is a classic two-player Tic Tac Toe game where players take turns marking spaces on a 3x3 grid. The player who succeeds in placing three marks in a row (horizontally, vertically, or diagonally) wins the game. If all nine spaces are filled without a winner, the game is a draw.

## Features

- Two-player gameplay (X and O)
- Win detection for all possible winning patterns
- Draw detection
- Reset button to clear the board and start a new game
- New Game button from the game over screen
- Clean and simple user interface
- Fully responsive design

## Project Structure

```
.
├── index.html      # Main HTML file with game board layout
├── style.css       # Styling for the game interface
├── app.js          # Game logic and event handling
├── package.json    # Project metadata and scripts
└── README.md       # This file
```

## Installation

No installation required! This project uses only vanilla JavaScript with no external dependencies.

## How to Run

### Option 1: Direct File Access
Simply open `index.html` in your web browser.

### Option 2: Using Node.js HTTP Server
If you have Node.js installed, you can run:

```bash
npm start
```

This will start a local HTTP server on port 8000. Open your browser and navigate to `http://localhost:8000`.

## How to Play

1. The game board is a 3x3 grid with 9 clickable boxes
2. Player 1 uses "O" and Player 2 uses "X"
3. Players take turns clicking on empty boxes to place their mark
4. The first player to get three marks in a row (horizontally, vertically, or diagonally) wins
5. If all 9 boxes are filled without a winner, the game is a draw
6. Click "Reset" to clear the board and start over
7. After a game ends, click "New Game" to play again

## Game Controls

- **Click any box** - Place your mark
- **Reset** - Clear the board and start a new game
- **New Game** - Start a fresh game after game over

## Technologies Used

- **HTML5** - Page structure
- **CSS3** - Styling and layout
- **JavaScript (Vanilla)** - Game logic and interactivity

## License

MIT License - feel free to use this project for learning or as a base for your own modifications!

## Winning Patterns

The game recognizes wins in the following patterns:
- Rows: [0,1,2], [3,4,5], [6,7,8]
- Columns: [0,3,6], [1,4,7], [2,5,8]
- Diagonals: [0,4,8], [2,4,6]

## Future Enhancements

Possible improvements for future versions:
- Single-player mode with AI opponent
- Difficulty levels
- Game statistics and scoring
- Different themes and styling options
- Sound effects
