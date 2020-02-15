# sudoku-solver

A simple web interface that solves sudoku puzzles using a backtracking algorithm. Try it [here](https://bblodfon.github.io/sudoku-solver/sudokuSolver.html)!

### Notes

- If the algorithm takes too long to find a solution, the execution is stopped and a message is shown.
- The puzzle generator is made using random variables, so some of the generated puzzles might be unsolvable (an appropriate message is shown when that happens)
- The number of `givens` when generating a new puzzle is **20** (can be changed in the [code](https://github.com/bblodfon/sudoku-solver/blob/master/sudokuSolver.js)).
