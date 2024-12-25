# Inconsistent `calc()` Results with Multiple Units in CSS

This repository demonstrates an uncommon issue encountered when using the CSS `calc()` function with a combination of percentages and multiple fixed units (pixels, ems, etc.).  The problem arises from inconsistencies in how different browsers interpret and evaluate these complex calculations, leading to unexpected results in the rendered layout.

## Bug Description
The `calc()` function, while powerful, can exhibit unpredictable behavior when combining percentages with multiple fixed-unit values within a single expression.  Browsers may not consistently handle the order of operations or unit conversions correctly, causing discrepancies in the final calculated value.

## How to Reproduce
1. Clone this repository.
2. Open `bug.css` to examine the problematic CSS code.
3. Open `index.html` (or any HTML that uses the CSS file) in different browsers (Chrome, Firefox, Safari, Edge).
4. Observe the differences in width of the affected element. You'll likely see variations depending on the browser and screen resolution.

## Solution
The solution presented in `bugSolution.css` provides a workaround to achieve consistent results. See the solution file for details.