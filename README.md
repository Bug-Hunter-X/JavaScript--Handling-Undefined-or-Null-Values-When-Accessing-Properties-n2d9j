# JavaScript: Handling Undefined or Null Values When Accessing Properties

This repository demonstrates a common error in JavaScript: attempting to access properties of undefined or null values.  The `bug.js` file contains code that will throw a `TypeError` if an undefined or null value is passed to the function. The `bugSolution.js` file provides a solution to this problem. 

## Problem
The function `foo` in `bug.js` attempts to access the `length` property of the input `x`. If `x` is `undefined` or `null`, this will cause a `TypeError`. 

## Solution
The solution in `bugSolution.js` includes a check to determine if `x` is `undefined` or `null` before accessing its `length` property.  If `x` is `null` or `undefined`, it returns 0. This prevents the `TypeError` from being thrown and provides a more robust function. 