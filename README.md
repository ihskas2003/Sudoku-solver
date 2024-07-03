# Sudoku-Suite
A C++17-compatible header that provides useful functions which help with the solving, validation and generation of 9x9 Sudoku puzzles. 
## Contents
* [Usage](#usage)
* [Documentation](#documentation)
* [Examples](#examples)
    * [Solving and validating a Sudoku puzzle](#solving-and-validating-sudoku-puzzle)
    * [Generating a Sudoku puzzle](#generating-a-sudoku-puzzle)
    * [Initialising and reusing Grid objects](#initialising-and-reusing-grid-objects)
    * [Reading Sudoku puzzles from a file](#reading-sudoku-puzzles-from-a-file)
    * [Operations on Grid objects](#operations-on-grid-objects)
* [How It Works](#sudoku-solver---how-it-works)
* [Running Tests](#running-tests)
* [Acknowledgements](#acknowledgements)
* [Tools](#tools)

## Usage 

* Simply download the `src/sudoku_suite.h` file and move it to your project's directory.
* Download the files in the `src/` directory and move it to your project's directory.
* Include the required header files, as shown below in the examples, and use the functions you need!
* **NOTE:** The code is incompatible with pre-C++17 versions. While compiling, you'll have to compile with the `--std=c++17` flag.
    * For example; when using the clang compiler, the compile command would be `c++ --std=c++17 /path/to/file.cpp`
