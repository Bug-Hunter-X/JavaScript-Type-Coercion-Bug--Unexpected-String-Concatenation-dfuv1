# JavaScript Type Coercion Bug

This repository demonstrates a common JavaScript bug related to type coercion. When adding a number and a string, JavaScript performs string concatenation instead of numerical addition, leading to unexpected results.

## Bug Description
The function `myFunction` takes two arguments and should return their sum. However, due to type coercion, when a number and a string are passed, the function concatenates the string and number instead of adding them numerically.

## Solution
The solution involves explicitly converting the input arguments to numbers before performing addition.  This ensures that numerical addition is always performed, regardless of the input types.

## How to run

1. Clone this repository.
2. Open `bug.js` and `bugSolution.js` to view the problematic code and its solution respectively.
3. Run the JavaScript files using Node.js (or your preferred JavaScript runtime).