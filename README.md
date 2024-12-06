## **Sokoban Game**

### **Project Title and Description**
**Sokoban Game** This is a classic puzzle game in which the player is supposed to push blocks into their corresponding targets. Features: many levels, a timer, step counter, undo/redo, level selection screen. The main focus for this implementation has been user interaction and game features.

---

### **Run Instructions**

#### **Prerequisites**
Before running the game, ensure you have the following installed:
1. **Python 3.11+**  
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
- `sokoban_loader.py` 
- Level images:
  - `level1-10x10.png`
  - `level2-7x9.png`
  - `level3-8x6.png`
  - `level4-8x6.png`

#### **How to Run**
1. Open your terminal or command prompt.
2. Navigate to the directory where the files are located.
3. Run the following command:
   ```bash
   python sokoban_player.py
   ```

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


