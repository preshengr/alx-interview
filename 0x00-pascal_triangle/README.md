Here's a structured README file based on your article:

---

# Pascal's Triangle

This project implements Pascal's Triangle in Python, generating a list of lists representing the triangle up to a specified number of rows.

## Table of Contents
1. [Introduction](#introduction)
2. [Task](#task)
3. [Directory Structure](#directory-structure)
4. [How to Use](#how-to-use)
5. [Testing](#testing)
6. [Author](#author)
7. [License](#license)

## Introduction
This project provides a Python implementation of Pascal's Triangle. Pascal's Triangle is a mathematical construct where each number is the sum of the two numbers directly above it. The triangle begins with a single 1 at the top and expands according to this rule.

## Task
The main objective of this project is to create a function, `pascal_triangle(n)`, that returns a list of lists of integers representing Pascal’s Triangle of size `n`. If `n` is less than or equal to 0, the function should return an empty list.

The provided test script, `0-main.py`, demonstrates the usage and expected output of the `pascal_triangle` function.

## Directory Structure

```
0x00-pascal_triangle/
│
├── 0-pascal_triangle.py  # Contains the implementation of the pascal_triangle function
├── 0-main.py             # Test script to verify the correctness of the pascal_triangle function
└── README.md             # Project documentation
```

## How to Use
To use this project, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/Official0mega/alx-interview.git
    cd alx-interview/0x00-pascal_triangle
    ```

2. Run the test script to see the output of the `pascal_triangle` function:

    ```bash
    ./0-main.py
    ```

   This will execute the `pascal_triangle` function and print the generated Pascal's Triangle for a given input.

## Testing
The project includes a test script (`0-main.py`) that you can run to verify the functionality of your `pascal_triangle` function. This script will display Pascal's Triangle based on the input provided.

```bash
./0-main.py
```

## Author
Precious Amaechi

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
