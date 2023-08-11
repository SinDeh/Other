# Other

This repository contains a collection of Python scripts that cover various topics and tasks. Each script is designed to perform a specific function or solve a particular problem. Below is a brief overview of the scripts available in this repository:

## Scripts

### 1. Conway's Game of Life
- File: `Conway_Game_of_Life.ipynb`
- Description: This repository contains a Python implementation of Conway's Game of Life using NumPy and Matplotlib.
#### Overview

Conway's Game of Life is a cellular automaton devised by mathematician John Conway. It is a zero-player game that simulates the evolution of a grid of cells based on a set of rules. Cells can be either alive or dead, and their states evolve over time based on the states of their neighbors.

#### Features

- Random initialization of the universe with alive cells.
- Calculation of neighbors for each cell.
- Simulation of the game according to the rules.
- Visualization of the evolving universe using Matplotlib.

### 2. Employee Attendance System with Face Recognition
- File: `face_detecting.ipynb`
- Description: This repository contains a Python script that utilizes face recognition to manage employee attendance. The script captures a live camera feed, compares detected faces with registered employee images, and logs attendance data along with timestamps.

#### Overview

The Employee Attendance System with Face Recognition is designed to automate attendance tracking using facial recognition technology. It leverages the `face_recognition` library for face encoding and comparison, and the `cv2` (OpenCV) library for camera access.

#### Features

- Automatic detection and recognition of employees using facial images.
- Real-time logging of employee attendance (entry and exit times) in a CSV file.
- Capability to clear attendance data if needed.

#### Prerequisites

- Python 3.x
- `face_recognition` library (install using `pip install face_recognition`)
- `cv2` library (OpenCV, install using `pip install opencv-python`)
- `pandas` library (install using `pip install pandas`)

### 3. Mastermind Game
- File: `mastermind_game.ipynb`
- Description: This repository contains a Python script that simulates the classic Mastermind game. In this game, the user sets a secret number for the program to guess, and vice versa. The program and the user take turns guessing and providing feedback, aiming to guess the opponent's number in the fewest attempts.

#### Overview

Mastermind is a code-breaking game where players attempt to guess the hidden code composed of numbers. This script offers a fun twist by allowing both the user and the program to take on the roles of the code maker and code breaker.

#### Features

- Interactive gameplay involving both the user and the program.
- Real-time feedback after each guess to refine the guessing strategy.
- Determination of the winner based on the number of attempts made by each side.

#### Rules

- The game supports numbers with a digit length between 1 and 10.
- The program and user take turns guessing the opponent's number.
- Feedback is provided after each guess to help refine the guesses.
- The winner is determined based on the fewest attempts taken by each side.

## How to Use

Each script comes with its own instructions and usage explanations. To run any script, make sure you have Python installed on your machine and execute the script using the command line or an integrated development environment (IDE).

## Contributing

Contributions to this repository are welcome! If you have any improvements, bug fixes, or new scripts to add, feel free to fork this repository, make your changes, and create a pull request.

---

Feel free to explore, use, and modify these scripts as needed. If you encounter any issues or have questions, please don't hesitate to reach out by creating an issue on GitHub.

Happy coding!
