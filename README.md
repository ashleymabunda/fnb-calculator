# Calculator – FNB App Academy

This is a fully functional calculator built using HTML, CSS, and JavaScript. It was developed as part of the FNB App Academy training program.

##  Features

###  Calculator Functions (JavaScript)
- **digitBtnPressed(button)**: Handles digit button presses and displays numbers in the input box. Supports chaining numbers.
- **btnACPressed()**: Clears the input display and resets the calculator.
- **operatorBtnPressed(operator)**: Stores the first number and the selected operator (`+`, `-`, `x`, `/`).
- **equalsBtnPressed()**: Evaluates the operation based on the operator and displays the result.

###  Logic Highlights
- **New Line Control**: The `newLine` boolean determines if the display should reset or append input.
- **Switch Statement**: Handles the calculation logic for all four arithmetic operations.

---

##  Styling Features (CSS)
- **Modern UI** using a smooth **blue gradient background** on all buttons:
  - `.digitButton`, `.operatorButton`, `.ACButton`, `.equalButton`
- **Rounded buttons** with subtle inner shadows (`box-shadow`)
- **Responsive layout** using a `<table>` for button structure
- **Styled input box**:
  - White background, rounded corners, right-aligned input
  - Clear and readable font (`2em`)
- **No borders** on individual `<td>` elements for a clean design

---

##  Files

- `calculator.html` – HTML structure and JavaScript logic (all in one)
- `style.css` – Styling for the calculator (input, table, buttons)

---

##  Technologies

- HTML5
- JavaScript (DOM, functions, events, switch)
- CSS3 (modern UI, gradients, shadows)

---

## creator

Ashley Mabunda  

