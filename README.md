# Case Converter Project

This project demonstrates two implementations of a case converter that transforms strings from PascalCase or camelCase into snake_case. The project includes both a **for loop-based** implementation and a **list comprehension-based** implementation.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Usage](#usage)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)

## Overview

The purpose of this project is to showcase Python programming techniques to solve the same problem in different ways. It takes a string in PascalCase or camelCase and converts it to snake_case by:
- Identifying uppercase characters.
- Adding an underscore (`_`) before each uppercase character.
- Converting uppercase characters to lowercase.
- Cleaning up any leading or trailing underscores.

## Features

- **Two implementations:**
  - Using a `for` loop for step-by-step conversion.
  - Using list comprehension for a more compact approach.
- Handles strings with mixed cases.
- Removes unwanted leading and trailing underscores.

## Usage

To run the project, execute the `main()` function in each implementation. You can pass any PascalCase or camelCase string to the `convert_to_snake_case` function to get the corresponding snake_case string.

### Running the Code
1. Clone the repository or copy the code into your Python environment.
2. Execute either of the scripts.
3. Observe the output of the case conversion.

```python
# Example command to run the script
python case_converter.py
