# ZeroDivisionError in Python Average Calculation

This repository demonstrates a common error in Python: the `ZeroDivisionError` that can occur when calculating the average of an empty list.  The original code lacks proper error handling, while the solution provides a robust fix.

## Bug Description
The `calculate_average` function fails if the input list is empty, leading to a `ZeroDivisionError`.  The solution addresses this by checking for an empty list and returning 0 in that case.

## Solution
The improved `calculate_average` function explicitly handles the empty list scenario, preventing the `ZeroDivisionError`.