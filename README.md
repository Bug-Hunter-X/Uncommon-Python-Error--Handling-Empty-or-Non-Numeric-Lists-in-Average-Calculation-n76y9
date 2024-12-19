This repository demonstrates a common yet subtle error in Python when calculating the average of a list of numbers. The provided code, `bug.py`, attempts to calculate the average, but fails gracefully when dealing with empty lists or lists containing non-numeric values. The solution, `bugSolution.py`, addresses these issues by adding more robust error handling.  The error is commonly encountered when the list is empty, leading to a `ZeroDivisionError`, or when the list contains non-numeric values, leading to a `TypeError`.  The solution shows how to prevent these errors and provide more user-friendly output.