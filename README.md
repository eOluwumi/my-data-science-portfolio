# Simple Web Calculator

A clean, public, browser-based calculator built with plain **HTML**, **CSS**, and **JavaScript**.

This repository now contains a lightweight calculator that can be hosted publicly using GitHub Pages.

## Features

- Addition, subtraction, multiplication, and division
- Decimal support
- Clear and delete controls
- Keyboard support
- Responsive interface
- No framework, no backend, no installation

## Project Structure

```text
.
├── index.html   # Calculator interface
├── style.css    # Calculator styling
├── script.js    # Calculator logic
└── README.md    # Project documentation
```

## Logic

The calculator stores user input as an expression string.

- Number/operator buttons append values to the display.
- `C` clears the display.
- `DEL` removes the last character.
- `=` evaluates the expression.
- Invalid expressions return `Error`.

## Keyboard Controls

- `0-9` for numbers
- `+`, `-`, `*`, `/` for operations
- `.` for decimals
- `Enter` or `=` to calculate
- `Backspace` to delete
- `Escape` to clear

## GitHub Pages

After enabling GitHub Pages from the repository settings, the calculator should be available at:

```text
https://eoluwumi.github.io/my-data-science-portfolio/
```

## Author

Built by Enoch Oluwumi.

> Small calculator today. Operating system of destiny tomorrow. One button at a time.
