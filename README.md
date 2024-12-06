## **Sokoban Game**

### **Project Title and Description**
**Sokoban Game** is a classic puzzle game where the player pushes blocks to their corresponding targets. The game includes multiple levels, a timer, step counter, undo/redo functionality, and a level selection screen. This implementation focuses on user interaction and features that enhance the gameplay experience.

---

### **Run Instructions**

#### **Prerequisites**
Before running the game, ensure you have the following installed:
1. **Python 3.9+**  
   Download from [python.org](https://www.python.org/downloads/).
2. **Required Libraries**:
   - `cmu_graphics`
   - `Pillow`

   To install these libraries, run the following commands:
   ```bash
   pip install cmu-graphics
   pip install pillow
   ```

#### **Game Files**
Make sure the following files are in the same directory:
- `sokoban_player.py` (main game file)
- `sokoban_loader.py` (level loading logic)
- Level images:
  - `level1-10x10.png`
  - `level2-7x9.png`
  - `level3-8x6.png`
  - `level4-8x6.png`
- `player.png` (player's image)

#### **How to Run**
1. Open your terminal or command prompt.
2. Navigate to the directory where the files are located.
3. Run the following command:
   ```bash
   python sokoban_player.py
   ```
4. The game window will open. Start playing!

---

### **Shortcut Commands**

#### **General Commands**
- **Arrow Keys (`↑ ↓ ← →`)**: Move the player in the respective direction.
- **`u`**: Undo the last move.
- **`r`**: Redo a move that was undone.
- **`a`**: Almost solve the level (only works on Level 1).
- **Any Key**: Return to the level selection screen after winning a level.

#### **Features**
- **Undo/Redo**: Press `u` to undo and `r` to redo moves. This allows you to explore different strategies without restarting the level.
- **Almost Solve**: Press `a` in Level 1 to test the game's "one move to solve" functionality.
- **Level Selection**: Use the mouse to click on a level in the title screen to start that level.

---

### **Game Features**
1. **Multiple Levels**: Includes 4 levels with increasing complexity.
2. **Timer and Step Counter**: Tracks the time and steps taken for each level.
3. **Level Selection Screen**: Navigate through levels using a graphical interface with previews.
4. **Win Screen**: Displays a congratulatory message when a level is completed.
5. **Undo/Redo**: Allows the player to undo and redo moves for more flexibility.

---
