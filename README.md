# Penalty-Shootout-Game
A penalty shootout game created using a Jupyter Notebook

Project Description:
- This current project is a Python penalty shootout style game, formed using a Jupyter Notebook.
- During this game, the player competes against the computer over five rounds of penalties. The player chooses a position to shoot; top left, bottom left, middle, top right, bottom right, whilst the computer goalkeeper makes a choice at random to dive to one of these same positions.
- The computer also takes a penalty each round, with the player's goalkeeper choosing a random position to dive to.
- After each round, the score is updated, and after five rounds of penalties, the team with the highest score count wins, should it be equal, the game ends as a draw.

How To Play:
1. Open the Jupyter Notebook
2. Run the Python code
3. Type out one of five positions into the text box provided
4. If the goalkeeper dives in the same position as you shoot, the penalty is saved, otherwise it is a goal
5. The computer then also takes a penalty each round
6. After five rounds, the final result is displayed
7. the player can then decide to play again or end the game

Game Features:
- A five-round penalty shootout
- Five possible positions to shoot
- Randomised goalkeeper diving positions and computer shot choice
- Input validation for both shot positions and replay vs end game decisions
- Two user-defined functions for both player and computer penalty decisions
- Score tracking for both teams after each round
- Win, loss and draw outcomes after each penalty shootout
- Option to replay the game again after finishing
- Global counters tracking; games played, games won, games lost and games drawn

Requirements To Play:
- Python 3
- Jupyter Notebook
- A built-in random module in Python
- No need for any additional Python packages

How To Run:
- Open the .ipynb game file in Jupyter Notebook and the game code cell to begin
- Follow all instructions which are displayed in the output

Tests Undertaken:
- Invalid shooting positions typed in text box
- Replay input validation
- Accurate goal and save scoring statistics
- Game statistics across several penalty shootouts
- Correct final game results and game termination
  - All tests were run and produced the expected outcomes successfully
