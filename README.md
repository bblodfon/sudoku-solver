# Sudoku Web puzzle solver
A simple web interface that solves sudoku puzzles using a backtracking algorithm. Some notes:
- If the algorithm takes too long to find a solution, the execution is stopped and a message is shown.
- The puzzle generator is made using random variables, so some of the generated puzzles might be unsolvable (an appropriate message is shown when that happens)
- The number of "givens" when generating a new puzzle is 20 (changeable in the script *sudokuSolver.js*).
- Try the puzzle solver [here](https://bblodfon.github.io/sudoku-solver/sudokuSolver.html)
