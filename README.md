# chess-like-game
⚔️ Hero's War – A Chess-like Strategy Game Hero's War is a turn-based, web-based strategy game inspired by chess, designed for two players on a compact 5x5 grid. With unique pieces and tactical gameplay, players must outsmart each other by capturing all opposing units to claim victory. 
![image](https://github.com/user-attachments/assets/6d11e47c-f121-403b-bcd7-76d14f969345)
⚔️ Chess-like Game ⚔️
Welcome to the Chess-like Game, a web-based, turn-based strategy game inspired by chess. The game is designed to be played by two players on a 5x5 grid. Each player commands a set of pieces with unique movement abilities. The objective is to outmaneuver and capture your opponent's pieces until one player remains victorious.

Note: To play the game, ensure that you open two browser tabs or windows. Each tab will represent a different player in the game. Both tabs need to be connected to the game server simultaneously for the game to function correctly.

🎮 Game Features
Real-Time Multiplayer: Play with another player in real-time through a WebSocket server.
Unique Grid Layout: A compact 5x5 grid that demands strategic thinking and quick decision-making.
Dynamic Piece Movement: Pieces have distinct movement patterns, creating complex tactical scenarios.
Victory Conditions: The game ends when one player captures all of the opponent's pieces.
📦 Deployed
You can run the Deployed version using the following link(Both players need to open this link):

https://satviksachan-21bce0423.vercel.app/

As this is a free Hosting site it sometimes due to inactivity takes time to connect therefore try below setup if issue persists

🚀 Installation and Setup
To get the game up and running locally, follow these steps:

Clone the repository to your local machine:
git clone https://github.com/satviksachan0/Hero-s-War
        
Navigate to the project directory:
cd Hero-s-War
        
Install the required dependencies:
npm install
        
Move to local branch
git checkout localDeploy
        
Start the server:
npm start
        
Open your web browser and navigate to http://localhost:8080 to start playing! Remember to open two tabs for a proper multiplayer experience.
📜 Game Rules
Grid: The game board consists of a 5x5 grid.
Pieces: Each player has several pieces, including "Pawn," "Hero1," and "Hero2," each with distinct movement abilities.
Turns: Players take turns moving one piece at a time. The current player is indicated at the bottom of the game screen.
Winning the Game: Capture all of your opponent's pieces.
Movement: Click on a piece to view its possible moves, highlighted on the grid. Click on a highlighted cell to move the piece.
🛠️ Technologies Used
Frontend: HTML, CSS, JavaScript
Backend: Node.js, Express, WebSocket
Version Control: Git, GitHub
