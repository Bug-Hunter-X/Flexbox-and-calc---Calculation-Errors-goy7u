# Flexbox and calc() Calculation Errors

This repository demonstrates a common issue when using the CSS `calc()` function with percentage values within flexbox containers.  The calculated width may not match expectations due to how flexbox handles percentage-based widths before the `calc()` function is processed. 

The `bug.css` file shows the problematic code.  The `bugSolution.css` file presents a possible solution, usually involving restructuring the layout or using different units.