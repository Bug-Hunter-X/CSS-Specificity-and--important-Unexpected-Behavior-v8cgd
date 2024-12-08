# CSS Specificity and !important Bug

This repository demonstrates an uncommon bug related to CSS specificity and the `!important` declaration. The bug highlights a situation where `!important` overrides specificity rules in an unexpected way.

## Bug Description
The bug involves a parent-child relationship in CSS where the child element has a style declaration with `!important`. Even when the parent-child selector has higher specificity, the `!important` declaration still takes precedence, producing unexpected results.

## How to Reproduce
1. Clone this repository.
2. Open `bug.css` and examine the code.
3. Open `bugSolution.css` for the solution and explanation.

## Solution
The solution avoids using `!important` whenever possible. Using more specific selectors generally helps resolve specificity-related issues.