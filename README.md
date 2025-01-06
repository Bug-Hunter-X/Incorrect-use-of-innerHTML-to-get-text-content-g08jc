# Uncommon HTML Bug: innerHTML vs. textContent

This repository demonstrates a common, yet subtle, error in HTML and JavaScript when extracting text from a div element.  Many developers incorrectly use `innerHTML` when they should use `textContent` to obtain only the textual content, excluding any HTML tags.

The `bug.html` file shows the incorrect use of `innerHTML`, while `bugSolution.html` provides the correct approach using `textContent`.

This bug can lead to unexpected behavior, especially when processing data retrieved from the DOM.