# JavaScript Null Handling Error

This repository demonstrates a common error in JavaScript: failing to handle null values appropriately.  The `bug.js` file shows the problematic code, while `bugSolution.js` provides a corrected version.

## Description

The original code doesn't explicitly check for `null` values before attempting to perform operations on them. This can lead to unexpected results or runtime errors. The improved code addresses this by adding a check for `null` at the beginning of the function. 

## How to run the code

1. Clone this repository.
2. Open `bug.js` and `bugSolution.js` in a text editor.
3. Open your browser's developer console or use `node` to run the JavaScript code. 

## Solution

The solution involves adding an explicit check for null values before performing any calculations. This prevents errors and ensures that the function behaves predictably even when null values are passed as arguments.