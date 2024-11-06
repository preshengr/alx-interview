```
# ALX INTERVIEW

Welcome to the **ALX INTERVIEW** repository! This repository contains solutions to a variety of interview preparation tasks and challenges, specifically tailored for the **ALX Software Engineering** program. Each task is organized into its own folder with solutions written in Python, C, or other relevant programming languages.

This repository is designed to help you strengthen your problem-solving skills, get comfortable with common interview questions, and gain hands-on coding experience with a range of practical coding exercises.

---

## Table of Contents
- [Repository Structure](#repository-structure)
- [Folders](#folders)
  - [0x00-pascal_triangle](#0x00-pascal_triangle)
  - [0x01-lockboxes](#0x01-lockboxes)
- [General Requirements](#general-requirements)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

---

## Repository Structure

Each folder in this repository represents a different challenge or coding problem. The folder names are prefixed with a unique identifier and describe the task or concept they contain. Here is a basic layout of the repository:

```plaintext
ALX INTERVIEW/
├── 0x00-pascal_triangle/
│   ├── README.md
│   └── pascal_triangle.py
├── 0x01-lockboxes/
│   ├── README.md
│   └── lockboxes.py
├── ...
└── README.md
```

Additional folders will be added over time, covering a wide range of interview preparation topics.

---

## Folders

### 0x00-pascal_triangle

**Description:** This folder contains a solution for generating Pascal's Triangle, a mathematical structure where each entry is the sum of the two directly above it. Pascal's Triangle is often used in combinatorics and probability.

- **Files:**
  - `pascal_triangle.py`: Function that returns a list of lists representing Pascal's Triangle up to a given number of rows.
  - `README.md`: Documentation specific to the Pascal's Triangle challenge, including example usage and expected output.

**Function Signature:**
```python
def pascal_triangle(n: int) -> List[List[int]]:
    """
    Generates Pascal's Triangle up to n rows.
    """
```

---

### 0x01-lockboxes

**Description:** This folder contains a solution to the "Lockboxes" problem. The objective is to determine if you can unlock all boxes given an initial set of keys in box 0 and each box potentially containing keys to other boxes.

- **Files:**
  - `lockboxes.py`: Function that returns `True` if all boxes can be opened, or `False` otherwise.
  - `README.md`: Documentation specific to the Lockboxes challenge, including example usage, explanations, and edge cases.

**Function Signature:**
```python
def canUnlockAll(boxes: List[List[int]]) -> bool:
    """
    Determines if all boxes can be unlocked.
    """
```

---

## General Requirements

- **Language:** Python 3.x (Other languages like C or JavaScript might be added in future folders)
- **Style Guidelines:** All Python code follows [PEP8](https://pep8.org/) conventions.
- **Testing:** Unit tests are included for each folder (when applicable) to ensure functionality.

### Additional Guidelines
- **README Files:** Each folder includes a `README.md` file providing specific information on the problem, the function signature, example inputs and outputs, and any special constraints.
- **Documentation:** Functions and classes are documented with clear docstrings to explain the purpose, parameters, return values, and any important notes.

---

## Usage

To use the solutions in this repository, you can clone the repository and execute the scripts directly or import them into your own Python files.

### Cloning the Repository
```bash
git clone https://github.com/your_username/ALX-INTERVIEW.git
cd ALX-INTERVIEW
```

### Running a Script
Navigate to the desired directory and run the script with `python3`. For example:

```bash
cd 0x00-pascal_triangle
python3 pascal_triangle.py
```

### Running Tests
Each folder may include a `tests/` directory or a single test file, depending on the challenge. To run the tests, navigate to the appropriate folder and execute:

```bash
python3 -m unittest discover tests
```

---

## Contributing

Contributions to this repository are welcome! If you'd like to add a new solution, fix bugs, or improve documentation, please follow these guidelines:

1. **Fork the repository** and make your changes in a new branch.
2. **Write or update tests** to ensure your code works as expected.
3. **Submit a pull request** with a detailed explanation of your changes.

Make sure to follow the repository's coding style and ensure that all new files include a `README.md` for documentation.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

**Happy Coding!**
```