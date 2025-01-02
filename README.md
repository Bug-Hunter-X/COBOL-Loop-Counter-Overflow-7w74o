# COBOL Loop Counter Overflow Bug

This repository demonstrates a common error in COBOL programs: integer overflow in a loop counter.

## Description
A simple COBOL program iterates through a loop, adding numbers.  If the counter variable is not defined with sufficient size, it will overflow, producing incorrect results.  This example highlights the importance of defining data types appropriately to handle the expected range of values.

## How to Reproduce
1. Compile and run `bug.cob`.
2. Observe the unexpected behavior caused by the loop counter's overflow.

## Solution
The `bugSolution.cob` file demonstrates the correction by properly sizing the counter variable to prevent overflow.
