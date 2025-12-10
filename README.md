# Dhanu-s-tic-tac-too


Tic Tac Toe Game

A simple, interactive Tic Tac Toe web application built using HTML, CSS, and JavaScript.
The game supports two players (X and O), detects winners automatically, and allows resetting the board anytime.

Features:
Clean and responsive UI layout.
Automatic turn switching between Player X and Player O.
Instant winner detection using predefined win patterns.
Displays winner message dynamically.
Includes a Reset button that refreshes the board.
Built entirely with vanilla JavaScript—no external libraries needed.


Technologies Used:
HTML5 – Structure of the game grid and UI.
CSS3 – Styling, layout (Flexbox), responsive centering.
JavaScript (ES6) – Game logic, event handling, and winner checking.
How to Run the Project
Download or clone the project folder.
Ensure the following files exist:
index.html
index1.css
index1.js
Open index.html in your browser.
Start playing by clicking any square in the grid.

Game Rules:
Player O always starts the game.
Players take turns clicking empty grid cells.
Once a player selects a box, it becomes disabled.
The game checks for a winner after every move.
If a winning pattern is detected, the winner is displayed.
Click Reset at any time to restart the game.


Folder Structure
project-folder/
│
├── index.html      # Main page
├── index1.css      # Styling file
├── index1.js       # Game logic
└── README.md       # Documentation

Winner Detection Logic
The game checks all 8 possible winning combinations:
[0,1,2], [3,4,5], [6,7,8],   # rows
[0,3,6], [1,4,7], [2,5,8],   # columns
[0,4,8], [2,4,6]             # diagonals
When all three positions contain the same symbol (X or O), that player wins.


Future Enhancements (Optional Improvements):
You can extend the game with exciting features such as:
Scoreboard for X and O.
AI opponent using minimax algorithm.
Animated UI transitions.
Sound effects on clicks and win announcements.
Dark mode toggle.

License:
This project is open-source and free to use for learning or personal projects.
