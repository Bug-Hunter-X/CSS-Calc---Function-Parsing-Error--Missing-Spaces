# CSS Calc() Function Parsing Error: Missing Spaces

This repository demonstrates a subtle bug related to the `calc()` function in CSS.  Some older or less common browsers might misinterpret the calculation if spaces around the operators are missing. 

The `bug.css` file contains the erroneous code, while `bugSolution.css` provides the corrected version.

**Problem:**
Missing spaces around the `-` operator within the `calc()` function can lead to unexpected results (incorrect width calculation) in some browsers.

**Solution:**
Ensure there are spaces around all arithmetic operators (+, -, *, /) within the `calc()` function.