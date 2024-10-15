# React Tic-Tac-Toe Game

A classic Tic-Tac-Toe game built with React, where two players can play against each other. The game includes real-time player name customization, turn tracking, and dynamic win/draw detection with a reset functionality.

Live version here: https://voluble-jelly-fb5d88.netlify.app/

## Features
- Player Management: Customize player names for "X" and "O".
- Game Board: Interactive 3x3 grid for selecting squares.
- Turn Logging: Keeps track of the sequence of moves.
- Win/Draw Detection: Automatically detects winning combinations or a draw.
- Game Reset: Ability to restart the game once it's over.

## Technologies Used
- React: To manage game state and UI components.
- CSS: For basic layout and styling.

## Project Structure
- App.js: Main component that controls the game flow, player turns, and winner/draw detection.
- Player.js: Manages player info and displays the current active player.
- GameBoard.js: Handles rendering the 3x3 grid and capturing square selections.
- Log.js: Displays a history of the turns made by the players.
- GameOver.js: Displays the winner or draw result and offers a reset option.
- winning-combinations.js: Stores the winning square combinations for easy win detection.

## How to Run

1. Clone the repository: git clone https://github.com/McTintor/tic-tac-toe-react.git
2. Navigate to the project directory: cd react-tic-tac-toe
3. Install dependencies: npm install
4. Start the development server: npm start
5. Open http://localhost:3000 to play the game in your browser.

## How It Works
- Player Turns: The game alternates turns between Player 1 ("X") and Player 2 ("O"). The active player is indicated visually.
- Move Selection: Players take turns selecting squares on a 3x3 grid. Selected squares are marked with the player's symbol.
- Win/Draw Detection: The game checks for winning combinations or a draw after each turn.
- Game Reset: When the game ends (win or draw), players can reset the board and start a new game.
