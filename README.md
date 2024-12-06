# CSS Specificity Gotcha: Selector Order Matters!

This repository demonstrates a subtle but important issue in CSS related to selector specificity and the order of your CSS rules.  While usually straightforward, the interaction of multiple selectors can lead to unexpected behavior if you're not careful about how you structure your stylesheet.

The `bug.css` file contains the problematic CSS. The `bugSolution.css` demonstrates a way to avoid the issue by ensuring the most specific selectors are placed correctly, or by consolidating selectors where possible to improve readability and reduce ambiguity.