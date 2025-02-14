# Unexpected behavior of calc() function in nested calculations

This repository demonstrates an unexpected behavior of the CSS `calc()` function when used with nested calculations involving percentages and pixel values.  The issue occurs when trying to calculate the width of an element dynamically based on its parent's width.

## Description
The `calc()` function in CSS is designed to perform calculations, allowing dynamic sizing based on different units. However, under certain circumstances, particularly when nested calculations are involved, the results might not always be as expected. This repository provides an example showcasing this issue and a proposed solution.

## Setup
1. Clone this repository.
2. Open `index.html` in your web browser.

## Issue
Examine `bug.css`.  You will see that the `width` of the `.element` class is unexpectedly incorrect due to the nested calculation within the `calc()` function. 

## Solution
The solution (`bugSolution.css`) demonstrates a work-around.  A more robust approach might involve restructuring the CSS or using JavaScript for more complex calculations.