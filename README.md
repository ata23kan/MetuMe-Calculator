# MetuMe Calculator
A basic calculator to be used in ME210 exams in Middle East Technical University.

## Key Features

### 1. Basic mathematics operations
* Includes standard (`sin`, `cos`, `tan`) and inverse (`sin⁻¹`, `cos⁻¹`, `tan⁻¹`) functions.
* Includes Natural Log (`ln`), Base-10 Log (`log`), and a flexible Base-n Log (`log_(`).
* Dedicated keys for square roots ($\sqrt{x}$), squares ($x^2$), and universal exponents ($x^y$).
* Supports both **Degrees (DEG)** and **Radians (RAD)**. You can toggle modes via the top-right menu.

### 2. Physical Constants
* Instant access to $\pi$ (3.1415...) and $e$ (2.7182...) for high-precision results.

### 3. Variable Storage
Specifically designed for multi-step engineering problems, you can store intermediate results to avoid rounding errors:
* Click **STO** then select a variable (**A, B, C, or D**) to store.
* Simply type the letter (A, B, C, or D) into your expression to call the stored variable.
* The last calculated value is stored in `Ans` variable. You can call it with the **Ans** button or simply type Ans from your keyboard.

### 4. Visual fractions
* The `⅟` key allows you to input fractions that render vertically, making complex quotients easier to read and verify.
* Use parantheses for a series of operations in the numerator and denominator.

### 5. Expression History
* The calculator remembers your last **10 evaluations**.
* Use the navigation arrows (**▲** and **▼**) to scroll through previous calculations. This is ideal for re-running a formula with a single value change.

## Keyboard Shortcuts
For faster input during exams, the calculator supports full keyboard mapping:

| Key | Action |
| :--- | :--- |
| **0-9** | Digits |
| + - * / | Basic Operators (Rendered as $+ − × ÷$) |
| **^** | Exponent ($x^y$) |
| **Enter  =** | Calculate |
| **( )** | Parentheses |
| **Backspace** | Delete last character |
| **Esc** | Clear All (AC) |
| **A, B, C, D** | Insert Variable |
| **Arrows (← →)** | Move cursor within the expression |
| **Arrows (↑ ↓)** | Navigate history |

You can type function names directly on your keyboard. Type the name and follow it with an opening parenthesis `(` to convert it:
* `sin(` $\rightarrow$ **sin(**
* `asin(` $\rightarrow$ **sin⁻¹(**
* `sqrt(` $\rightarrow$ **√(**
* `pi` $\rightarrow$ **π**
