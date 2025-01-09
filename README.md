# Tailwind CSS Gradient Background Rendering Issue

This repository demonstrates a bug where a Tailwind CSS gradient background doesn't render correctly in some browsers.  The issue specifically arises when using `bg-gradient-to-r` with specific color palettes.

## Bug Description

A simple Tailwind CSS gradient is implemented using `bg-gradient-to-r from-blue-500 to-purple-500`. However, this gradient is rendered incorrectly or not at all in some browsers.  This inconsistency creates a cross-browser compatibility problem.

## Solution

The solution involves ensuring that the appropriate prefixes are included in the CSS, ensuring proper browser compatibility.

## Steps to Reproduce

1. Clone this repository.
2. Open `bug.js` and `solution.js` to view the problematic and corrected code.
3. Open `index.html` in various browsers to observe the rendering discrepancies.

## Technologies Used

* Tailwind CSS
* HTML
* JavaScript (for demonstration)
