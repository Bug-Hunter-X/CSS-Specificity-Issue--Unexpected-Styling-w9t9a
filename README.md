# CSS Specificity Issue

This repository demonstrates a common CSS issue related to specificity.  The `bug.css` file contains code with conflicting style rules due to specificity. The solution is provided in `bugSolution.css` and addresses the conflict by carefully considering CSS selector specificity.

## Problem:

The CSS in `bug.css` results in unexpected styling because a more specific selector overrides another. This can lead to confusion and debugging challenges.

## Solution:

`bugSolution.css` offers a solution by either modifying the specificity of selectors or using `!important` (use this sparingly) to explicitly enforce a style rule, demonstrating the different ways to manage conflicting styles in CSS.  Understanding specificity is crucial for writing maintainable and predictable CSS.