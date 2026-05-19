# SimpleCalculator

A sleek, modern, and highly responsive web calculator built from scratch using vanilla frontend technologies. This project features a clean dark-themed user interface, native keyboard support, and a structured object-oriented JavaScript architecture.

## ✨ Key Features & Technical Implementations

* **Object-Oriented JavaScript Architecture:** Engineered using an ES6 `Calculator` class encapsulation to cleanly manage state transitions, clear operations, digit deletions, and computations.
* **Advanced Input Validation & Precision Control:** * Implemented strict decimal point constraints to block duplicate dot inputs per operand.
  * Handled floating-point precision anomalies (e.g., preventing errors like `0.1 + 0.2 = 0.30000000000000004`) using targeted truncation formatting.
  * Integrated crash protection logic to handle divide-by-zero operations securely with descriptive user alerts.
* **Full Keyboard Event Mapping:** Bound native document keydown event listeners to match numeric inputs, arithmetic operators (`+`, `-`, `*`, `/`, `%`), execution triggers (`Enter`, `=`), and cleanup shortcuts (`Backspace`, `Escape`).
* **Modern CSS Grid Layout & Micro-Interactions:** * Built a perfectly aligned mathematical keypad using a fluid 4-column CSS Grid setup.
  * Crafted realistic button press mechanics featuring smooth cubic-bezier scale transitions (`transform: scale(0.92)`) upon user activation.

---

## 🛠️ Tech Stack & Concepts Demonstrated

* **Structure:** Semantic HTML5 utilizing declarative `data-*` attributes (`data-number`, `data-operation`, `data-action`) for clean separation of concerns between layout and behavioral logic.
* **Styling:** Modern CSS3 featuring linear gradient backdrops, absolute centering Flexbox & Grid properties, explicit gap spacing definitions, and responsive break-word display wrapping.
* **Logic:** JavaScript (ES6+ Class structures, event tracking, conditional control switches, and DOM tree updating mechanics).

---

## 📂 Project Structure

```
Calculator
├── index.html    # Markup structure and data-attribute definitions
├── style.css        # Keypad CSS Grid layout, color palettes, and active scaling
└── script.js        # Calculator state logic, arithmetic solvers, and keyboard events

```
