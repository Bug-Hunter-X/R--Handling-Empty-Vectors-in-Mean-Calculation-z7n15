# R: Handling Empty Vectors in Mean Calculation

This repository demonstrates a common error in R when calculating the mean of an empty vector and provides a solution.

## Bug
The `bug.R` file contains code that attempts to calculate the mean of an empty numeric vector.  This results in a warning message from R because the `mean()` function cannot handle empty vectors directly.

## Solution
The `bugSolution.R` file provides a robust solution that gracefully handles empty vectors by checking for their length before calculating the mean. This prevents the warning message and provides a more reliable result.

## How to run the code
1. Clone this repository.
2. Open `bug.R` and `bugSolution.R` in your preferred R editor.
3. Run each file separately using R's source() function or by copying and pasting the code into an R console.

This example highlights the importance of defensive programming in R, particularly when working with potentially empty vectors or other data structures.