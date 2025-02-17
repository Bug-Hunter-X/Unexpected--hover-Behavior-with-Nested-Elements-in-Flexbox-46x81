# Unexpected :hover Behavior with Nested Elements in Flexbox

This repository demonstrates a peculiar issue where the `:hover` pseudo-class in CSS doesn't behave as expected when applied to a nested element within a flexbox container.  The hover effect only applies when the cursor is directly over the inner element, and not when hovering over the parent container.

The `bug.css` file contains the problematic CSS code. The `bugSolution.css` demonstrates a solution to this problem. 

## Bug Description
The hover effect should apply to the child element when the cursor is over either the parent or the child element.  However, in the provided code, the effect only works when directly over the child element.

## Solution
The issue is resolved by changing the order of the selectors in the CSS rule.