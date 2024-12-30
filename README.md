# Unexpected NaN Result in Addition Function

This repository demonstrates a subtle bug in a JavaScript addition function that produces an unexpected NaN result when one of the inputs is NaN. The bug and its solution are provided in separate JavaScript files.

## Bug Description

The `foo` function adds two numbers.  While it correctly handles null inputs by returning 0, it does not handle NaN values appropriately, returning NaN instead of a more meaningful result (e.g., 0 or an error message).

## Solution

The `bugSolution.js` file provides a corrected version of the function that explicitly checks for NaN inputs and returns a default value (0) in those cases.