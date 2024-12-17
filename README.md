# Uncommon HTML Bug: Typo in Element Selection

This repository demonstrates a subtle yet easily missed bug in HTML involving a typo in the method used to select an element using JavaScript. The incorrect use of `document.getElementByID` instead of the correct `document.getElementById` can lead to unexpected behavior and errors that are difficult to debug.

## Bug Description

The bug lies in the JavaScript code within the `bug.html` file.  There is a typo in the function used to obtain a reference to the HTML element with the id "myDiv". The code attempts to use `document.getElementByID`, but the correct method is `document.getElementById`. This will result in the script failing to update the content of the div.

## Solution

The solution, provided in `bugSolution.html`, corrects the typo, resulting in the expected behavior. The correct function call is `document.getElementById`.