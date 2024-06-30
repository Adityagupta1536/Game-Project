Here's the corrected markdown format for your README files:

## Stone Paper Scissors Game

### Overview
This is a simple implementation of the classic game "Stone Paper Scissors" (Rock Paper Scissors) in JavaScript. The game allows the user to play against the computer.

### Technologies Used
- HTML
- CSS
- JavaScript

### Features
- Single-player mode against the computer
- Random computer choices
- User input for selecting stone, paper, or scissors
- Win/loss/tie detection

### Game Logic
1. **User Input:** The game prompts the user to choose between stone, paper, or scissors.
2. **Computer Choice:** The computer randomly selects its move.
3. **Result Determination:** The game logic compares the user's choice with the computer's choice to determine the winner:
   - Stone crushes scissors
   - Scissors cuts paper
   - Paper covers stone
4. **Output Result:** The game displays the result (win/loss/tie) to the user and may prompt for another round.

### Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

### License
This project is licensed under the MIT License - see the LICENSE file for details.

### DEMO VIDEO
[Rock Paper Scissors Game]((https://github.com/Adityagupta1536/Game-Project/tree/main/Games/Stone%20Paper%20%26%20scissor))                   | [Live Demo](https://github.com/Adityagupta1536/Game-Project/Games/StonePaper&Scissors/) |

### Author
**Name:** Aditi Mishra  
**Roll No:**  
**Email:** aditimishra7511@gmail.com

---

## Tic Tac Toe Game

### Overview
This is a simple implementation of the classic game "Tic Tac Toe" in JavaScript. The game can be played by two players.

### Technologies Used
- HTML
- CSS
- JavaScript

### Features
- Two-player mode
- Basic game interface
- Win, X, 0 & Draw detection

### How It Works
1. **User Input:** Players take turns to place their marks (X or O) on the board.
2. **Game Board:** The board is a 3x3 grid where players place their marks.
3. **Win/Tie Detection:** The game checks for a win (three marks in a row, column, or diagonal) or a tie (no more empty spaces and no winner).
4. **Output Result:** The game announces the result (win/tie) and play for another round.

### Game Logic
- **Board Representation:** The board is represented as a 2D array or list.
- **Player Turns:** Players alternate turns to place their marks.
- **Win Conditions:** Check all rows, columns, and diagonals for three identical marks.
- **Tie Condition:** Check if all spaces are filled without a winner.

### Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

### DEMO VIDEO
 ./Tic Toc Toe.mp4


### License
This project is licensed under the MIT License - see the LICENSE file for details.

### Author
**Name:** Ansh Vishnoi  
**Roll No:** 36  
**Email:** vishnoiansh25@gmail.com

---

## Tetris Game

### Introduction
Tetris is a tile-matching puzzle video game originally designed and programmed by Alexey Pajitnov. This project recreates the classic game with a modern twist, implemented using HTML5, CSS, and JavaScript.

### Technologies Used
- HTML
- CSS
- JavaScript

### Usage
To start the game, open the `index.html` file in a web browser.

### Controls
- Arrow keys: Move tiles
- ctrl+R: Restart the game
- Q: For Rotate

### Game Logic
- **Tile Generation:** A new tile (2 or 4) appears at a random empty position on the grid after each move.
- **Tile Movement:** Tiles slide in the direction of the player's input (left, right, up, down).
- **Tile Merging:** When two tiles of the same number collide, they merge into one tile with their sum.
- **Score Calculation:** The score increases by the value of the merged tiles.
- **Game Over:** The game ends when there are no valid moves left (no empty spaces and no adjacent tiles with the same number).

### How the Game Works
1. **Initialization:** The game initializes a 4x4 grid with two randomly placed tiles (2 or 4).
2. **Tile Movement:** Players use the arrow keys to slide all tiles in the chosen direction. Tiles slide until they hit the edge of the grid or another tile.
3. **Tile Merging:** When two tiles with the same number collide, they merge into one tile with their combined value. The merged tile cannot merge again in the same move.
4. **New Tile Generation:** After each move, a new tile (2 or 4) appears at a random empty position on the grid.
5. **Score Calculation:** The player's score increases by the value of the tiles merged in that move.
6. **Game Over:** The game checks for possible moves after each move. The game ends if there are no valid moves left (no empty spaces and no adjacent tiles with the same number).

### Future Enhancements
- Enhanced animations and effects
- Leaderboard to track high scores
- Additional game modes (e.g., timed mode, challenge mode)
- Improved AI for better tile generation

### Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

### DENO VIDEO
./tetris .mp4

### License
This project is licensed under the MIT License - see the LICENSE file for details.

### Author
**Name:** Anviksha Srivastava  
**Roll No:** 64  
**Email:** anvikshashrivastav@gmail.com

---

## 2048 Game

### Introduction
2048 is a single-player sliding block puzzle game. The game was developed by Gabriele Cirulli and has gained widespread popularity due to its simple yet addictive gameplay. This project recreates the game using HTML5, CSS3, and JavaScript.

### Technologies Used
- HTML
- CSS
- JavaScript

### Usage
To start the game, open the `index.html` file in a web browser.

### Controls
- Arrow keys: Slide the tiles
- R: Restart the game


## How to Play
- Use the arrow keys (up, down, left, right) to move the tiles.
- When two tiles with the same number collide, they merge into one with the sum of the two tiles.
- The goal is to create a tile with the number 2048.
- The game is over when there are no possible moves left.

## Game Logic
1. **Grid Initialization**: The game starts with a 4x4 grid with two randomly placed tiles, each with a value of either 2 or 4.
2. **Tile Movement**: Tiles are moved in the direction of the arrow keys pressed. All tiles move as far as possible in the selected direction until they either hit the edge of the grid or another tile.
3. **Tile Merging**: When two tiles with the same value collide, they merge to form a new tile with their combined value. After each move, a new tile (with a value of 2 or 4) is added to a random empty spot on the grid.
4. **Winning and Losing Conditions**: The player wins by creating a 2048 tile. The game ends when there are no empty spaces and no possible moves left.


## Future Enhancements
- **Undo Feature**: Allow players to undo their last move.
- **Online Multiplayer Mode**: Implement a competitive mode where players can compete against each other in real-time.
- **AI Solver**: Implement an AI that can play the game and achieve high scores.
- **Mobile Optimization**: Improve the game’s performance and usability on mobile devices.
- **Theme Customization**: Allow players to choose different themes and tile designs.

### DEMO VIDEO
[2048- Game]((https://github.com/Adityagupta1536/Game-Project/tree/main/Games/2048-Game))                   | [Live Demo](https://github.com/Adityagupta1536/Game-Project/Games/2048-Game/) |


### Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

### License
This project is licensed under the MIT License - see the LICENSE file for details.

### Author
**Name:** Aditya Gupta  
**Roll No:**  
**Email:** adityagupta1536@gmail.com
