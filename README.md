# Incorrect Null Handling in JavaScript Function

This repository demonstrates a common error in JavaScript functions: incorrect handling of null values. The `foo` function is designed to add two numbers. However, it returns `null` when either input is null, instead of the expected behavior of returning 0 in such cases.

The `bug.js` file contains the erroneous code, while `bugSolution.js` provides the corrected implementation.

## How to reproduce

1. Clone this repository.
2. Run `node bug.js` to see the incorrect output.
3. Run `node bugSolution.js` to see the corrected output.