# JavaScript Unexpected NaN Behavior

This repository demonstrates a common JavaScript issue where a function designed to handle null values unexpectedly produces NaN when given an undefined input.  The `foo` function in `bug.js` illustrates this problem. The solution, found in `bugSolution.js`, provides a corrected version of the function using a more robust check for both null and undefined values.