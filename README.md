# CSS Specificity Bug

This repository demonstrates a common issue in CSS related to specificity conflicts.  The `bug.css` file contains CSS code that unexpectedly applies styles due to the way CSS handles selector specificity. The `bugSolution.css` shows how to resolve this issue.

The problem arises from conflicting selectors.  Understanding and managing CSS specificity is critical for avoiding unexpected behavior.

## How to Reproduce

1. Open `bug.css`
2. Note that the element with ID `unique` and class `special` will not be styled as expected due to specificity.

## Solution

Examine the `bugSolution.css` file for a solution that addresses the specificity problem using techniques such as more specific selectors or the `!important` flag (used cautiously).

## Learning Points

This example highlights the importance of understanding CSS specificity.  When writing CSS, it is essential to be aware of how different selectors interact and their relative priorities. Tools and techniques to help manage CSS specificity include:

*   Using developer tools (like those in Chrome or Firefox) to inspect the calculated styles applied to an element.
*   Being mindful of the order in which you declare your styles.
*   Using a CSS preprocessor like Sass or Less to help organize and manage complex stylesheets.
*   Understanding the specificity calculation rules (inline styles > IDs > classes > elements).