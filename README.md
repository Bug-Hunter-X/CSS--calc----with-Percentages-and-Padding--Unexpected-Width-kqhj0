# CSS `calc()` with Percentages and Padding: Unexpected Width

This repository demonstrates an uncommon CSS issue related to the `calc()` function, percentages, and padding. The problem arises when calculating a width using `calc(50% - 20px)`, expecting a width of 50% minus 20 pixels. However, the padding is not considered when the 50% is calculated, leading to an unexpected wider element.

The `bug.css` file contains the problematic code. The `bugSolution.css` file provides a solution by explicitly using the `box-sizing` property to handle padding differently.

## Bug Report
The bug is described in the bug report found in the JSON file associated with this repository.  The core problem lies in the interplay of percentage width calculation and padding's effect on the final rendered width.