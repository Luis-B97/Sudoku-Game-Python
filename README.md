# Sudoku Game - Python Edition

A fully-featured Sudoku game built with Python and Pygame, developed as a final project for COP3502.

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![Pygame](https://img.shields.io/badge/Pygame-2.x-green.svg)

## Features

- **Interactive GUI**: Clean, user-friendly interface built with Pygame
- **Multiple Difficulty Levels**: Easy, Medium, and Hard modes
- **Sudoku Generator**: Automatically generates valid Sudoku puzzles
- **Input Validation**: Real-time checking for valid moves
- **Game Controls**: Sketch mode, cell selection, reset functionality
- **Visual Feedback**: Highlights selected cells and provides error indicators

## Screenshots

![Sudoku Game](8bit-gator.png)

## Installation

### Prerequisites
- Python 3.x
- Pygame library

### Setup

1. Clone the repository:
```bash
git clone https://github.com/Luis-B97/Sudoku-Game-Python.git
cd Sudoku-Game-Python
```

2. Install dependencies:
```bash
pip install pygame
```

3. Run the game:
```bash
python sudokumain.py
```

## How to Play

1. **Select Difficulty**: Choose Easy, Medium, or Hard at the start screen
2. **Click a Cell**: Click on any empty cell to select it
3. **Enter Numbers**: Use keyboard (1-9) to fill in numbers
4. **Sketch Mode**: Press a number key to sketch possibilities
5. **Finalize Answer**: Press Enter to lock in your answer
6. **Reset**: Click the Reset button to start over
7. **Restart**: Click Restart to generate a new puzzle

## Game Controls

| Key/Action | Function |
|------------|----------|
| **1-9** | Enter number in selected cell |
| **Enter** | Confirm sketched number |
| **Mouse Click** | Select cell |
| **Reset Button** | Clear all user inputs |
| **Restart Button** | Generate new puzzle |
| **Exit Button** | Quit game |

## Project Structure
```
Sudoku-Game-Python/
├── sudokumain.py           # Main game loop and GUI
├── sudoku_generator.py     # Sudoku puzzle generation and solving logic
├── 8bit-gator.png         # Game assets
└── README.md              # This file
```

## Technical Details

### Sudoku Generation Algorithm
- Uses backtracking algorithm to generate valid puzzles
- Ensures unique solutions for each difficulty level
- Randomly removes cells based on difficulty:
  - Easy: 30 cells removed
  - Medium: 40 cells removed  
  - Hard: 50 cells removed

### Game Logic
- **Cell Class**: Manages individual cell state (value, sketched, selected)
- **Board Class**: Handles 9x9 grid, validation, and game state
- **GUI Components**: Pygame-based interface with button interactions

## Development

This project was developed as a final project for COP3502 (Programming Fundamentals).

### Team Contributors
- 3 team members collaborated on this project
- Roles included: Game logic, GUI design, and puzzle generation

## Future Enhancements

- [ ] Add hint system
- [ ] Implement timer/scoring system
- [ ] Save/load game state
- [ ] Add sound effects
- [ ] Multiplayer mode
- [ ] Mobile version

## Technologies Used

- **Python 3.x**: Core programming language
- **Pygame**: Game development library
- **Backtracking Algorithm**: For puzzle generation and solving

## What I Learned

- Object-oriented programming in Python
- Game development with Pygame
- Algorithm implementation (backtracking, recursion)
- Team collaboration and version control with Git
- GUI design and user experience considerations

## License

This project was created for educational purposes as part of COP3502.

## Acknowledgments

- University of Florida - COP3502 Course
- Pygame Documentation
- Team members for their contributions

## Contact

For questions or feedback, feel free to reach out through GitHub!

---

**Note**: This was a collaborative group project. All team members contributed to different aspects of the implementation.