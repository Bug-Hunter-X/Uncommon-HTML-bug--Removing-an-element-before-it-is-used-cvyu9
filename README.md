# Uncommon HTML Bug: Removing an element before it is used

This repository demonstrates an uncommon HTML bug where a script attempts to remove a DOM element before the script execution, causing unexpected behavior. The bug stems from the improper ordering of operations.

## Bug Description
The provided HTML file demonstrates a common error related to removing an element with JavaScript.  The script attempts to remove the element with id "myDiv", however, this removal happens before the script has a chance to execute.

## Bug Solution
The solution restructures the code to ensure that the element is accessed and removed after the page is fully loaded or at least after the element is fully rendered.

## How to Reproduce
1. Clone this repository.
2. Open `bug.html` in your browser.
3. Observe that the element is not removed as expected.
4. Open `bugSolution.html` to see the corrected version of the code.
