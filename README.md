# Off-by-One Error in Java Array

This repository demonstrates a common off-by-one error in Java when iterating through an array.  The error occurs because the loop condition `i <= arr.length` should be `i < arr.length` to avoid accessing the element beyond the array's bounds. The solution corrects this error to prevent the exception.

## Bug
The `Bug.java` file contains the code with the off-by-one error. Running this code will result in an `ArrayIndexOutOfBoundsException`.

## Solution
The `BugSolution.java` file presents the corrected code with the appropriate loop condition to avoid the error.  This corrected code iterates through the array correctly, preventing the exception.
