# CSS `calc()` Silent Failure: A Common Pitfall

This repository demonstrates a subtle but common error in CSS that can lead to frustrating debugging sessions: the silent failure of the `calc()` function due to syntax errors.  The `calc()` function is powerful, but a small mistake can render it completely useless without any obvious indication from the browser.

The `bug.css` file shows the erroneous code.  The `bugSolution.css` file demonstrates how to correct the error.

**Problem**: When there's a syntax error in your `calc()` expression, the browser often doesn't throw an error. It simply ignores the entire `calc()` expression, resulting in unpredictable layout and visual discrepancies.

**Solution**: Carefully review your `calc()` expressions for errors like missing parentheses or operators, ensuring proper spacing and operator precedence.