# CSS Specificity Bug

This repository demonstrates a common CSS bug related to specificity issues when styling HTML elements with multiple CSS selectors.  The bug arises from the interaction of ID, class, and universal selectors and how CSS determines which styles to apply in cases of conflicting declarations.

## Bug Description
The `bug.css` file contains CSS rules that aim to style a button element using different selectors (ID, class, and universal). However, due to specificity issues and possibly CSS parsing order, the button's final style may not match the expected result. 

## Solution
The `bugSolution.css` file provides a solution to resolve this specificity issue and ensure the correct style is applied to the button element.  By understanding and correctly managing CSS specificity, the intended style can be achieved consistently across browsers.

## How to Reproduce
1. Clone this repository.
2. Open `index.html` in a web browser.
3. Observe the button's background color. It might be different from the expected color (green) due to the specificity conflict.