# Sudoku Web puzzle solver
A simple web interface that solves sudoku puzzles using a backtracking algorithm. Some notes:
- If the algorithm takes too long too find a solution I stop the execution and show a message.
- The puzzle generator is made using random variables, so some of the generated puzzles might be unsolvable (an appropriate message is shown when that happens)
- The number of "givens" when generating a new puzzle is 20 (changeable in the script sudokuSolver.js).
