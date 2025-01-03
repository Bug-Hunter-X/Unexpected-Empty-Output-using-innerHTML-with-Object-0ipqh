# Unexpected Empty Output using innerHTML with Object

This example demonstrates an uncommon error in HTML where using innerHTML with a JavaScript object instead of a string results in an unexpected empty output. The bug is in `bug.html`, and the corrected version is in `bugSolution.html`.  The solution involves converting the object to a string before assigning it to innerHTML.

## Setup

1. Clone the repository.
2. Open `bug.html` in a web browser.
3. Observe the empty div.
4. Open `bugSolution.html` to see the corrected version.

## How to reproduce the bug

1. Open `bug.html` in your browser.
2. The div with the id "myDiv" will remain empty.