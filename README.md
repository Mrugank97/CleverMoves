# **CleverMoves**
### Smart Game Engine

#### Overview
This project, conducted under the guidance of Prof. Balagopal Komarath at IIT Gandhinagar, focuses on creating a repository of intelligent game implementations where the computer employs optimal strategies to make moves. The games implemented include Sudoku and Tic-Tac-Toe, each designed with advanced algorithms to ensure the computer makes the best possible moves to challenge the player or solve the game efficiently.

#### Repository Contents
- **Tic-Tac-Toe (4x4)**
  - A Tic-Tac-Toe game with a 4x4 board where the computer decide the best move.
  - Includes functions for initializing the board, printing the board, checking for a win or draw, and determining the best move for the computer.
  - Allows for human vs. computer gameplay with real-time move evaluations.

- **Sudoku Solver**
  - A Sudoku solver capable of solving any standard 9x9 Sudoku puzzle.
  - Utilizes a backtracking algorithm to fill in the board while ensuring all constraints are met.
  - The solver can be used to verify if a given Sudoku puzzle is solvable and provides the solution if it exists.

#### Features
- **Optimal Move Selection**
  - Ensures the computer plays optimally, providing a challenging experience for the player in Tic-Tac-Toe.
  - Guarantees efficient and correct solutions for Sudoku puzzles.

- **Scalable and Extensible**
  - Code is modular and well-documented, allowing for easy extension to other games or enhancements to existing ones.
  - Clear separation of game logic and user interface facilitates adaptability and integration with other systems.

- **Interactive and User-Friendly**
  - Interactive command-line interface for Tic-Tac-Toe allows users to play against the computer with ease.
  - Sudoku solver can be used directly from the command line or integrated into larger applications.
  

#### Usage
To play Tic-Tac-Toe or solve a Sudoku puzzle, compile the respective C/C++ files and run the executable. Follow the on-screen instructions to interact with the game or provide the Sudoku puzzle to be solved.

```sh
# Compile Tic-Tac-Toe
g++ -o tictactoe tictactoe.c

# Run Tic-Tac-Toe
./tictactoe

# Compile Sudoku Solver
g++ -o sudoku sudoku.cpp

# Run Sudoku Solver
./sudoku < puzzle.sudoku
```

#### Future Work
- **Additional Games**: Extend the repository to include other classic games like Chess, Checkers, or Go with intelligent move algorithms.
- **GUI Integration**: Develop graphical user interfaces for each game to enhance user experience.
- **Performance Optimization**: Optimize algorithms for larger boards and more complex games to ensure efficient performance.

#### Contributors
- **Primary Developer**: Mrugank Patil
- **Advisor**: Prof. Balagopal Komarath, IIT Gandhinagar