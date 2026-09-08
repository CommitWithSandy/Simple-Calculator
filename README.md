# Simple Calculator

A lightweight, interactive calculator built with vanilla HTML, CSS, and JavaScript. Perfect for performing basic arithmetic operations with a modern, user-friendly interface.

## Features

✨ **Core Functionality**
- Addition, Subtraction, Multiplication, and Division
- Decimal point support for precise calculations
- Clear button to reset all values
- Delete button to remove the last digit
- Division by zero protection

🎨 **Design**
- Modern gradient background
- Responsive grid-based button layout
- Color-coded buttons for easy navigation:
  - **Gray**: Number buttons
  - **Blue**: Operators (+, -, *, /)
  - **Green**: Equals button
  - **Red**: Clear button
  - **Orange**: Delete button
- Smooth hover and active button animations
- Clean, minimalist interface

## File Structure

```
simple-calculator/
├── index.html      # HTML structure and layout
├── styles.css      # Styling and responsive design
├── script.js       # Calculator functionality
└── README.md       # Documentation
```

## How to Use

1. **Clone the repository** or download the files
2. **Open `index.html`** in your web browser
3. **Click buttons** to enter numbers and operations
4. **Press `=`** to calculate the result
5. **Use `C`** to clear all values
6. **Use `DEL`** to remove the last digit

## Calculator Operations

| Operation | Symbol | How to Use |
|-----------|--------|-----------|
| Addition | + | Click numbers, then `+`, then more numbers, then `=` |
| Subtraction | - | Click numbers, then `-`, then more numbers, then `=` |
| Multiplication | * | Click numbers, then `*`, then more numbers, then `=` |
| Division | / | Click numbers, then `/`, then more numbers, then `=` |
| Clear | C | Clears the display and resets all values |
| Delete | DEL | Removes the last digit from the current input |
| Decimal | . | Click to add a decimal point |

## Example Calculations

- **2 + 3 = 5**
- **10 - 4 = 6**
- **6 * 7 = 42**
- **20 / 4 = 5**
- **3.5 + 2.5 = 6**

## Technical Details

### JavaScript Functions

- **`appendNumber(num)`** - Appends a digit to the current input
- **`appendOperator(op)`** - Sets the operator for the calculation
- **`calculate()`** - Performs the calculation based on selected operator
- **`clearDisplay()`** - Resets all values to default
- **`deleteLast()`** - Removes the last character from input
- **`updateDisplay()`** - Updates the display with current input

### Error Handling

- ✅ Prevents division by zero with an alert message
- ✅ Prevents multiple decimal points in a single number
- ✅ Handles edge cases gracefully

## Browser Compatibility

Works on all modern browsers that support:
- HTML5
- CSS3 (Flexbox, Grid, Gradients)
- ES6 JavaScript

## Installation

No installation required! Simply:

```bash
git clone https://github.com/CommitWithSandy/simple-calculator.git
cd simple-calculator
# Open index.html in your browser
```

## License

This project is open source and available for personal and educational use.

## Author

Created by Sandesh Hiremath

---

**Happy Calculating! 🧮**
