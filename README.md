Sure, here is the corrected README file with appropriate bash commands and explanations:

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
   git clone https://github.com/YashwanthKakani/Sudoku-Game.git
   cd Sudoku-Game
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

## Acknowledgements

- Thanks to the Pygame community for their helpful resources and support.
- Inspired by classic Sudoku puzzles.

---

Enjoy playing Sudoku King!
```

### Explanation

1. **Features**: Lists the main features of the game.
2. **Installation**: Provides step-by-step instructions for setting up the project locally.
    - **Clone the repository**: Instructions on how to clone the repository from GitHub and navigate into the project directory.
    - **Install the required dependencies**: How to install dependencies using `pip`.
    - **Ensure Pygame is installed**: How to install Pygame.
3. **Usage**: 
    - **Run the game**: Command to start the game.
    - **Select the difficulty level**: Instructions on how to select the difficulty level.
    - **Input numbers**: How to select a cell and input numbers.
    - **Check board state**: How to check if the board state matches the solution.
    - **Auto-solve**: How to auto-solve the puzzle.
4. **Game Controls**: Lists the controls for interacting with the game.
5. **Code Structure**: Brief explanation of the main scripts in the project.
6. **Contributing**: Guidelines for contributing to the project.
7. **Acknowledgements**: Credits to contributors and inspirations.

Make sure to replace the placeholder links for images with the correct URLs from your GitHub repository once you upload the images. Save this content as `README.md` in your project's root directory.
