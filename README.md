# Sudoku Solver Using Backtracking

This is a Sudoku Solver application built using Pygame. The solver uses the backtracking algorithm to solve the Sudoku puzzle.

## Features

- Visual representation of the Sudoku board.
- Ability to input numbers and solve the puzzle using the backtracking algorithm.
- Reset the board to default or clear the board for a new puzzle.

## Installation

1. Ensure you have Python installed. You can download it from [python.org](https://www.python.org/).
2. Install the required libraries using pip:
    ```bash
    pip install pygame requests
    ```

## Usage

1. Run the `sudoku_solver.py` script:
    ```bash
    python sudoku_solver.py
    ```
2. The Sudoku window will open. You can interact with the board using your mouse and keyboard.

## Controls

- **Mouse Click**: Select a cell.
- **Number Keys (1-9)**: Input a number into the selected cell.
- **Enter**: Solve the puzzle.
- **R**: Clear the board.
- **D**: Reset the board to default.

## Code Overview

- `draw()`: Draws the Sudoku grid and numbers.
- `draw_box()`: Highlights the selected cell.
- `draw_val(val)`: Draws the value entered by the user.
- `raise_error1()`, `raise_error2()`: Displays error messages.
- `valid(m, i, j, val)`: Checks if a value is valid in the current cell.
- `solve(grid, i, j)`: Solves the Sudoku puzzle using backtracking.
- `instruction()`: Displays instructions for the game.
- `result()`: Displays the result when the puzzle is solved.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Pygame community for their support and resources. Check out [pygame.org](https://www.pygame.org/contribute.html) for more information.

