# Roman Numeral Converter

A simple web-based tool to convert numbers into Roman numerals. Built with HTML, CSS, and JavaScript.



---

## Features

- Converts numbers from **1 to 3999** into Roman numerals.
- Validates input to ensure only valid numbers are processed.
- Displays error messages for invalid inputs (e.g., negative numbers, non-numeric values, or numbers ≥ 4000).
- Responsive design for use on desktop and mobile devices.

---

## How It Works

The converter uses a straightforward algorithm:
1. It iterates through a list of Roman numeral values and symbols.
2. For each value, it appends the corresponding symbol to the result while subtracting the value from the input number.
3. This process repeats until the input number is reduced to zero.

---