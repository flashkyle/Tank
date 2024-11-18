# Tank Trouble: Battle Chronicles

## **Overview**
Tank Trouble: Battle Chronicles is a modern reimagining of the classic game Tank Trouble. In this project, players control tanks in maze-like environments, engage in strategic battles with bouncing projectiles, and navigate challenges as part of a plot-driven adventure. The game is built using the **CMU Graphics framework** and demonstrates mastery of Python programming concepts.

---

## **Features**
- **Tank Movement:** Smooth, interactive controls for player movement and aiming.
- **Projectile Mechanics:** Fire bouncing projectiles that interact with walls and other tanks.
- **Dynamic Mazes:** Randomly generated maze layouts to enhance replayability.
- **Storyline Elements:** Narrative progression through objectives and challenges.

---

## **Setup Instructions**
1. **Prerequisites:**
   - Python 3.x installed.
   - CMU Graphics framework installed (part of course materials).

2. **How to Run:**
   - Clone or download the repository to your local machine.
   - Open a terminal and navigate to the project directory.
   - Run the game with the following command:
     ```bash
     python main.py
     ```

3. **Directory Structure:**
   ```plaintext
   TankTroubleProject/
   ├── main.py             # Entry point for the game
   ├── src/                # Contains all source code
   │   ├── tank.py         # Tank class
   │   ├── projectile.py   # Projectile class
   │   ├── maze.py         # Maze generation and collision detection
   │   ├── game_logic.py   # Overall game logic
   │   └── __init__.py     # (optional) Package initialization
   └── README.md           # Project documentation
