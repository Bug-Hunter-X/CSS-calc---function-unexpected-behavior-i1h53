# CSS `calc()` Function Unexpected Behavior

This repository demonstrates a common issue encountered when using the `calc()` function in CSS.  The `calc()` function, while powerful for dynamic calculations, can produce unexpected results if not used correctly.  Specifically, this example showcases the importance of proper spacing and unit inclusion within the calculation.

## Bug
The bug involves incorrect usage of the `calc()` function, leading to unexpected width calculations.  The provided `bug.css` file demonstrates this behavior. The solution is shown in `bugSolution.css`

## Solution
The solution involves adding spaces around the minus operator and ensuring all values within the `calc()` function have appropriate units.