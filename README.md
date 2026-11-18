# Python Code Examples

A collection of beginner-friendly Python scripts demonstrating basic control flow, arithmetic operations, and console input/output.

## Features

- Calculate the factorial of a non-negative integer
- Print the requested number of Fibonacci sequence terms
- Calculate the square of an integer or decimal number
- No third-party libraries or dependencies required

## Requirements

- Python 3
- A terminal or command-line interface

No package installation is required.

## Installation

Clone the repository and enter the project directory:

```bash
git clone https://github.com/ayushbishnoi900-byte/python-code.git
cd python-code
```

## Usage

Run each script with Python and follow the prompt in the terminal.

### Factorial

Calculate the factorial of a number:

```bash
python3 factorial.py
```

Example:

```text
Enter a number: 5
Factorial = 120
```

The script computes `n!` using a `for` loop. Entering a negative number produces `Factorial = 1` because the loop does not execute; the script does not currently validate negative input.

### Fibonacci Sequence

Print a sequence of Fibonacci terms:

```bash
python3 fibonacci.py
```

Example for 7 terms:

```text
Enter the number of terms: 7
0 1 1 2 3 5 8
```

The first two generated values are `0` and `1`. Each following value is the sum of the two preceding values.

### Square

Calculate the square of a number:

```bash
python3 square.py
```

Example:

```text
Enter a number: 4.5
Square = 20.25
```

This script accepts both integers and decimal values.

## Project Structure

```text
python-code/
├── factorial.py   # Calculates the factorial of an integer
├── fibonacci.py   # Prints Fibonacci sequence terms
├── square.py      # Calculates the square of a number
└── README.md      # Project documentation
```

## Implementation Notes

- `factorial.py` uses an iterative loop to calculate factorial values.
- `fibonacci.py` maintains two variables and updates them iteratively.
- `square.py` uses Python's exponent operator (`**`) to perform multiplication.
- Input is converted to an integer or float as required by each script.

## Contributing

Contributions are welcome. To contribute:

1. Fork the repository.
2. Create a feature branch.
3. Make your changes.
4. Submit a pull request.

Please keep changes small and ensure that each Python script runs successfully before submitting.