# My Projects

A collection of beginner-friendly Python practice scripts focused on core programming fundamentals.

[![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

---

## Overview

This repository contains simple, well-structured Python scripts designed for learning and practicing essential programming concepts such as user input, type conversion, string operations, and loops.

| Script       | Description                                      | Concepts Covered                  |
|--------------|--------------------------------------------------|-----------------------------------|
| `ls29.py`    | Concatenates three user-provided values          | Input handling, string operations |
| `ls31.py`    | Prints a sequence of numbers from 1 to *n*       | Type conversion, `for` loops      |

---

## Scripts

### 1. Number Concatenation — `ls29.py`

Accepts three values from the user and concatenates them as strings.

**How it works**
1. Prompts the user for three inputs
2. Treats all inputs as strings
3. Prints the concatenated result

**Example**
```bash
$ python ls29.py
Enter a number: 10
Enter another number: 20
Enter a third number: 30
102030
```

---

### 2. Number Sequence Printer — `ls31.py`

Reads an integer *n* and prints every integer from 1 to *n* (inclusive).

**How it works**
1. Reads a single integer from standard input
2. Uses a `for` loop with `range(n)`
3. Prints each number on its own line

**Example**
```bash
$ python ls31.py
5
1
2
3
4
5
```

---

## Requirements

- **Python 3.x** (no external packages required)

---

## Getting Started

### Clone the repository
```bash
git clone https://github.com/TMINUSOMEGA/Myprojects.git
cd Myprojects
```

### Run a script
```bash
python ls29.py
# or
python ls31.py
```

---

## Project Structure

```
Myprojects/
├── ls29.py          # String concatenation practice
├── ls31.py          # Number sequence printer
└── README.md        # Project documentation
```

---

## Learning Goals

These scripts help reinforce:

- Reading user input with `input()`
- Converting strings to integers with `int()`
- Basic string concatenation
- Using `for` loops and `range()`
- Writing clean, readable code

---

## Contributing

Contributions are welcome! Feel free to:

- Fork the repository
- Add new practice scripts
- Improve existing code or documentation
- Open a pull request

---

## License

This project is open source and available under the [MIT License](LICENSE).
