# Unexpected Behavior in CSS `calc()` Due to Spacing and Operator Precedence

This repository demonstrates a potential issue with the CSS `calc()` function related to unexpected behavior caused by improper spacing and operator precedence.

## Problem

The `calc()` function in CSS allows for calculations within style declarations. However, incorrect spacing or a misunderstanding of operator precedence can lead to unexpected results and layout issues.

The included `bug.css` file shows an example where incorrect spacing and missing parentheses cause the `calc()` function to not produce the expected results.

## Solution

The solution provided in `bugSolution.css` addresses these problems by correcting the spacing and adding parentheses to enforce the correct order of operations, ensuring that `calc()` produces the desired outcome.

## How to Reproduce

1. Clone the repository.
2. Open `bug.html` (or a similar HTML file that includes the CSS). 
3. Observe the unexpected behavior caused by the `bug.css` styles.
4. Replace `bug.css` with `bugSolution.css` and observe the correct behavior. 