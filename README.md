# Responsive Calculator

A clean, simple calculator built with plain HTML, CSS, and JavaScript — no frameworks or dependencies required. Just open the file in a browser and start calculating.

## Features

- Basic arithmetic operations: addition, subtraction, multiplication, and division
- Percentage (`%`) support
- Clear (`C`) and delete-last-character (`DEL`) buttons
- Decimal point support
- Responsive, card-style UI with hover effects on buttons
- Error handling for invalid expressions (displays `Error`)

## Demo

Open `Index.html` in any modern web browser — no build step or server needed.

## Tech Stack

- **HTML5** – structure and markup
- **CSS3** – styling, layout (flexbox), and button hover transitions
- **JavaScript (Vanilla)** – calculator logic and DOM manipulation

## Project Structure

```
Responsive-calculator-main/
├── Index.html   # Calculator markup, styles, and script (all-in-one)
└── README.md    # Project documentation
```

## Getting Started

1. Clone or download this repository.
2. Open `Index.html` directly in your browser (double-click it, or right-click → Open With → Browser).
3. Start calculating!

No installation, build tools, or dependencies are required.

## How It Works

- Number and operator buttons append their value to the display via `appendValue()`.
- `C` clears the display; `DEL` removes the last character.
- `=` evaluates the current expression using JavaScript's `eval()` and shows the result, or `Error` if the expression is invalid.

## Usage

| Button | Action                          |
|--------|----------------------------------|
| `C`    | Clear the entire display         |
| `DEL`  | Delete the last entered character|
| `%`    | Percentage operator              |
| `÷`    | Division                         |
| `×`    | Multiplication                   |
| `−`    | Subtraction                      |
| `+`    | Addition                         |
| `.`    | Decimal point                    |
| `=`    | Evaluate the expression          |

## Notes

- The calculator uses JavaScript's `eval()` to evaluate expressions. This is fine for a simple personal/demo project but is generally best avoided in production apps, as `eval()` can execute arbitrary code if untrusted input is passed to it.

## License

This project is open source and free to use for learning or personal purposes.
