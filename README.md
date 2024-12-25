# Uncommon HTML Bug: innerHTML on Non-Existent Element

This repository demonstrates a subtle but important bug in HTML: attempting to access and modify the `innerHTML` property of an element that does not exist.  This results in a JavaScript error that is not always easy to detect.

The `bug.html` file shows the problematic code. The `bugSolution.html` file presents the corrected approach which involves checking for the existence of the element before attempting any modification.