# RAM Machine Simulator
Welcome to my RAM machine simulator repository! This project is a simulation of a RAM (Random Access Machine) that I created as my final project for the Introduction to C course at UWr in 2022. The purpose of this project is to provide a tool for understanding and experimenting with the workings of a RAM machine.

## Features:
- Uses doubly-linked lists to store and manipulate data
- Initializes all untouched memory cells to 0
- Simulates a tape by initializing all memory cells along the way
- Input and output files are formatted as newline-separated integers

## Code Structure:
The code is divided into several main parts:

- Main Menu: the main function that runs the program
- Menu functions: auxiliary functions for the menu, including file input/output
- Engine: the core of the simulator that contains pointers to input/output tapes and command tape
- Tapes: structures for input/output tapes and command tape
- Memory: structure for the accumulator

## How to Use:
To use this simulator, you can clone this repository and compile the code using a C compiler. Once compiled, you can run the executable and follow the menu prompts to load an input file, run the simulation, and output the results to a file.