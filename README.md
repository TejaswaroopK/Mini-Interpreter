# Mini Interpreter

A simple web-based interpreter that supports variable declarations with `let` and basic conditional expressions using `if-then-else` syntax.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Usage](#usage)
- [Supported Syntax](#supported-syntax)
- [Example](#example)
- [Technologies Used](#technologies-used)
- [Author](#author)
- [License](#license)

---

## Overview

This Mini Interpreter lets you write simple code snippets with variable declarations and conditional logic in an easy-to-use web interface. It evaluates expressions and prints the result of the last expression or conditional.

---

## Features

- Variable declaration and assignment using `let` statements.
- Conditional evaluation using `if (condition) then expr else expr`.
- Supports arithmetic expressions with variables.
- Displays errors for invalid syntax or undefined variables.
- Clean and responsive UI for quick testing.

---

## Usage

1. Enter your code in the textarea.
2. Click the **Run** button.
3. The output or error message will appear below.

---

## Supported Syntax

- **Variable Declaration:**  
  `let variableName = expression;`  
  Example: `let x = 5;`

- **Conditional Expression:**  
  `if (condition) then expression else expression`  
  Example: `if (x < 10) then x else 10`

- **Expressions:**  
  Arithmetic expressions using variables and numbers.  
  Example: `x + 5 * 2`

- Each statement should be separated by a semicolon `;`.

---

## Example

```plaintext
let x = 5;
let y = 10;
if (x < y) then y else x
