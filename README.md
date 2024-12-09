# JavaScript Null/Undefined Handling Bug

This repository demonstrates a common error in JavaScript: improper handling of `null` or `undefined` function arguments.  The `bug.js` file shows a function that fails when null values are passed. The solution, `bugSolution.js`, shows how to correctly handle these cases to prevent unexpected errors or crashes.

**How to reproduce the bug:**
1. Run `bug.js`.
2. Call `foo()` with `null` or `undefined` as arguments.
3. Observe the potential error or unexpected behavior.

**How to fix the bug:**
1. Implement robust checks for `null` or `undefined` values at the beginning of your functions.
2. Handle these cases gracefully (e.g., return a default value, throw an error, or log a warning).