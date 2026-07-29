# Calculator Web Application

A sleek, responsive, and fully functional browser-based calculator built using **HTML5**, **CSS3 (CSS Grid & Flexbox)**, and **Vanilla JavaScript**.

---

## ✨ Features

*   **Core Arithmetic:** Supports addition (`+`), subtraction (`-`), multiplication (`x`), and division (`/`).
*   **Advanced Functions:** Includes modulus/remainder calculation (`Rem`), single-character deletion (`Del`), and full screen clearing (`AC`).
*   **Convenience Inputs:** Dedicated buttons for decimals (`.`) and double zeros (`00`).
*   **Modern UI:** Clean dark-mode interface styled with custom HSL colors, responsive grid alignment, and rounded buttons.

---

## 🛠️ Technologies Used

*   **HTML5** for page structure
*   **CSS3** (CSS Grid, Flexbox, and HSL color styling) for layout and design
*   **JavaScript (ES6+)** for event handling, string manipulation, and calculations

   ---

## 📁 Project Structure

```text
├── p7.html      # Main structural layout
├── p7.css       # Layout styles and theme configurations
└── p7.js        # Calculator logic and calculation functions
```

---

## 🚀 How to Run Locally

1. Clone or download this project folder to your local machine.
2. Open the project directory in a code editor (such as Visual Studio Code).
3. Open `index.html` directly in any modern web browser, or use a tool like **Live Server** in VS Code for local previewing.

---

## ⚙️ JavaScript Functions Overview

*   `addToDisplay(input)`: Appends numbers, decimals, or operators to the display screen.
*   `clearDisplay()`: Resets the input box completely (`AC`).
*   `del()`: Uses string slicing (`.slice(0, -1)`) to remove the rightmost character.
*   `calculate()`: Evaluates the active mathematical expression string using JavaScript's `eval()` method.
