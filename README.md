# Append to an Integer Variable in Go
This example demonstrates a common error in Go: attempting to append to an integer variable.  Go's integers are not slices or arrays, thus the append function is not applicable.

This repository contains:

- `bug.go`: The code demonstrating the error.
- `bugSolution.go`: A corrected version of the code.