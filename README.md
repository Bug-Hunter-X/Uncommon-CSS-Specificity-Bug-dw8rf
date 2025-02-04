# Uncommon CSS Specificity Bug
This repository demonstrates an uncommon bug related to CSS specificity and nested selectors. The bug occurs when dealing with nested elements and selectors and is related to the cascading nature of CSS. The bug is triggered when a specific selector that should logically override others does not, leading to unexpected behavior. 

## How to Reproduce
1. Clone the repository.
2. Open `bug.html` in a web browser.
3. Observe the width of the element with the ID "id-container". The width is unexpectedly not 100px but rather 300px, due to a subtle error in CSS Specificity

## Solution
The solution involves understanding and adjusting the specificity of the selectors involved to enforce the intended precedence. Refer to the `bugSolution.css` file for the fix.