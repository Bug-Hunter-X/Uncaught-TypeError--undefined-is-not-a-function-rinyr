# Uncaught TypeError: undefined is not a function
This repository demonstrates a common JavaScript error: "Uncaught TypeError: undefined is not a function."  The error arises from attempting to call a function that hasn't been defined or is inaccessible in the current scope.  The solution shows how to properly define and call functions, handling potential cases where arguments might be missing.

## Bug
The `bug.js` file contains the erroneous code.  The `foo` function is called with insufficient arguments in one case, leading to an error.

## Solution
The `bugSolution.js` file demonstrates how to handle missing function arguments using default parameters or conditional checks before calling the function to avoid the `Uncaught TypeError`. 