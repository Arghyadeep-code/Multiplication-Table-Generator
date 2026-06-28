# Multiplication Table Generator

A small interactive Python script that generates the multiplication table for any integer up to a limit you choose.

## Description

This repository contains a single script (`calc.py`) that prompts the user for a number and a limit, then prints the multiplication table from 0 up to the specified limit (inclusive).

## Features
- Minimal, dependency-free Python script
- Interactive: enter the base number and upper limit at runtime
- Prints results in a clear "n x i = product" format

## Requirements
- Python 3.x (Python 3.6+ recommended)

## Usage
1. Open a terminal/command prompt.
2. Clone the repository (optional) and change into the repository folder:

   git clone https://github.com/Arghyadeep-code/Multiplication-Table-Generator.git
   cd Multiplication-Table-Generator

3. Run the script:

   python calc.py

   (If your system requires `python3` instead of `python`, run `python3 calc.py`.)

4. When prompted, enter the integer whose multiplication table you want to generate and then enter the upper limit.

Example session:

- Prompt: which number's multiplication table do you want to generate?
  - User types: 7
- Prompt: till how much do you want to generate?
  - User types: 10

Output:

7  x  0  =  0
7  x  1  =  7
7  x  2  =  14
...
7  x  10  =  70

## How to open
1. Open a terminal or command prompt.
2. Navigate to the project directory (where `calc.py` is located). If you cloned the repo use:

   cd Multiplication-Table-Generator

3. Run the script with Python:

   python calc.py

   or, if your system requires it:

   python3 calc.py

4. Follow the on-screen prompts to enter the base number and the maximum multiplier. The script will print the multiplication table from 0 up to the value you entered.

## Notes and suggestions
- The current implementation reads integer inputs using `int(input(...))`. Non-integer input will raise a ValueError.
- You can easily extend the script to validate input, support negative numbers, or format output differently (for example, aligning columns).

## License
This project is provided as-is. Feel free to use and modify it for learning purposes.
