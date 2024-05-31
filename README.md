
```markdown
# Sudoku King

Sudoku King is an interactive Sudoku puzzle game implemented using Pygame. The game allows users to select a difficulty level, solve the puzzle manually, or use an auto-solve feature.

## Features

- Interactive Sudoku grid where users can input numbers.
- Auto-solve feature to complete the entire puzzle automatically.
- Difficulty levels to choose from.
- Visual feedback for correct and incorrect inputs.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/YashwanthKakani/Sudoku-Game
   cd sudoku-king
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Ensure Pygame is installed:

   ```bash
   pip install pygame
   ```

## Usage

1. Run the game:

   ```bash
   python GUI.py
   ```

2. Select the difficulty level:
    ![image](https://github.com/YashwanthKakani/Sudoku-Game/assets/146508049/0f2ec8a2-82d5-4376-9a01-def2aabc5707)

   - Level 1: Easy
   - Level 2: Medium
   - Level 3: Hard

3. Click on an empty cell to select it and use the keyboard to input numbers.

4. Press `Enter` to check if the current board state matches the solution.

5. Press `C` to auto-solve the entire puzzle.
![image](https://github.com/YashwanthKakani/Sudoku-Game/assets/146508049/6a947d33-589f-4735-9698-83ffa1e56289)


## Game Controls

- **Mouse Click**: Select a cell.
- **Number Keys (1-9)**: Input a number into the selected cell.
- **Enter**: Check if the board state matches the solution.
- **C**: Auto-solve the puzzle.

## Code Structure

- `GUI.py`: Main game script.
- `sudokuSolverAlgo.py`: Sudoku solving algorithm.
- `chooseLevel.py`: Function to select difficulty level.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

1. Fork the repository.
2. Create a new branch: `git checkout -b my-feature-branch`
3. Make your changes and commit them: `git commit -m 'Add new feature'`
4. Push to the branch: `git push origin my-feature-branch`
5. Open a pull request.

## Acknowledgements

- Thanks to the Pygame community for their helpful resources and support.
- Inspired by classic Sudoku puzzles.

---

Enjoy playing Sudoku King!




