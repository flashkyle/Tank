**README.md
Sokoban Game
Project Title and Description
Sokoban Game is a classic puzzle game where the player pushes blocks to their corresponding targets. The game includes multiple levels, a timer, step counter, undo/redo functionality, and a level selection screen. This implementation focuses on user interaction and features that enhance the gameplay experience.

Run Instructions
Prerequisites
Before running the game, ensure you have the following installed:

Python 3.11+
Download from python.org.

Required Libraries:
cmu_graphics
Pillow
To install these libraries, run the following commands:
pip install cmu-graphics
pip install pillow
Game Files
Make sure the following files are in the same directory:

sokoban_player.py (main game file)
sokoban_loader.py (level loading logic)

Level images:
level1-10x10.png
level2-7x9.png
level3-8x6.png
level4-8x6.png


How to Run
Open your terminal or command prompt.
Navigate to the directory where the files are located.
Run the following command:
python sokoban_player.py
The game window will open. Start playing!

Shortcut Commands
General Commands
Arrow Keys (↑ ↓ ← →): Move the player in the respective direction.
u: Undo the last move.
r: Redo a move that was undone.
a: Almost solve the level (only works on Level 1).
Any Key: Return to the level selection screen after winning a level.
Features
Undo/Redo: Press u to undo and r to redo moves. This allows you to explore different strategies without restarting the level.
Almost Solve: Press a in Level 1 to test the game's "one move to solve" functionality.
Level Selection: Use the mouse to click on a level in the title screen to start that level.
Game Features
Multiple Levels: Includes 4 levels with increasing complexity.
Timer and Step Counter: Tracks the time and steps taken for each level.
Level Selection Screen: Navigate through levels using a graphical interface with previews.
Win Screen: Displays a congratulatory message when a level is completed.
Undo/Redo: Allows the player to undo and redo moves for more flexibility.
