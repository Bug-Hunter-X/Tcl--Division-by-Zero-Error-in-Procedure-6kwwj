# Tcl Bug: Division by Zero

This repository demonstrates a common error in Tcl: unhandled division by zero. The `bug.tcl` file contains a procedure that can result in a runtime error if called with inappropriate arguments. The `bugSolution.tcl` file provides a corrected version.

## Bug Description

The `badproc` procedure in `bug.tcl` does not check for a zero divisor before performing the division.  When called with 0 as the first argument, this results in a runtime error.

## Solution

The corrected `badproc` procedure in `bugSolution.tcl` includes a check for a zero divisor, preventing the runtime error.  It returns an appropriate value (or throws an error) in cases where the divisor is zero. 