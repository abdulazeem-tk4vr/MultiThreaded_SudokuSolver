# MultiThreaded Sudoku Solver

MultiThreaded Sudoku Solver which can solve a valid NxN Sudoku.

## Features

- **Parallelism with Multithreading:** The program takes advantage of parallelism by implementing multi-threading using pthreads in C.
- **Dynamic Thread Spawning:** The program spawns 'N' threads depending on the input whenever it encounters an empty cell.
- **Efficient Execution:** The code was optimized for speed and correctness, running in approximately '0' seconds, and helped me secure a spot in the top 10 of the class leaderboard.

## Installation

To compile and run the project, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/MultiThreaded_SudokuSolver.git
    ```
2. Navigate to the project directory:
    ```bash
    cd MultiThreaded_SudokuSolver
    ```
3. Compile the code:
    ```bash
    gcc -o sudoku_solver sudoku_solver.c -lpthread
    ```

## Usage

To run the program, use the following command:
```bash
./sudoku_solver input_sudoku.txt
