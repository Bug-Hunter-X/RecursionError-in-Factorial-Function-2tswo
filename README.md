# RecursionError in Python Factorial Function
This repository demonstrates a common error in recursive functions: forgetting to handle the base case properly, leading to infinite recursion. The example is a factorial function that doesn't correctly handle negative input values.

The `bug.py` file contains the faulty code, which throws a `RecursionError` when a negative number is provided as input.

The solution, `bugSolution.py`, addresses this by adding an explicit check for negative input, returning an error message or handling it appropriately.