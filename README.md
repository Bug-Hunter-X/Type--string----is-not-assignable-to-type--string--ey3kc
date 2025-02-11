# Type 'string[]' is not assignable to type 'string'
This repository demonstrates a common TypeScript error: assigning an array of strings to a variable expecting a single string.

The `bug.ts` file contains the erroneous code. The `bugSolution.ts` file provides a corrected version.

## Problem
The `greeter` function expects a single string argument. However, the code attempts to pass an array of strings. TypeScript correctly flags this as a type error.

## Solution
The solution involves either modifying the `greeter` function to accept an array of strings or modifying the way the `user` variable is handled to provide a single string to the function.  The `bugSolution.ts` shows the preferred solution (modifying the variable to pass the appropriate data type).