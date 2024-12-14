# Unhandled undefined in length check

This repository demonstrates a common JavaScript error: attempting to access the `length` property of an undefined value.

The `bug.js` file contains the erroneous code. The `bugSolution.js` file provides a corrected version.

The error occurs because the `foo` function doesn't explicitly handle the case where the input `x` is `undefined`.  Accessing `x.length` when `x` is `undefined` results in a `TypeError`.

The solution adds a check for `undefined` before accessing `x.length`, preventing the error.