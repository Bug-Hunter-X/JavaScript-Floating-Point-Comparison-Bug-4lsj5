# JavaScript Floating-Point Comparison Bug

This repository demonstrates a common yet subtle bug in JavaScript related to comparing floating-point numbers for equality.

## The Bug
The `foo` function in `bug.js` attempts to compare two numbers for equality. However, due to the inherent limitations of floating-point representation, this comparison can yield unexpected results.

## The Solution
The `bugSolution.js` file offers a corrected approach. Instead of directly comparing floating-point numbers for equality, it uses a tolerance to check if the difference between the numbers is within an acceptable range. This addresses the precision issues associated with floating-point numbers. 