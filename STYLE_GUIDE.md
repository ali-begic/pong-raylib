# Style Guide for Pong

This document outlines the coding style and conventions to follow for the **Pong** project. Consistent code style helps improve readability and maintainability.

## General Guidelines

- **Follow a consistent coding style**: Adhere to conventions used in the existing codebase.
- **Use meaningful names**: Choose clear and descriptive names for variables, functions, and classes.
- **Write clear and concise comments**: Comment your code to explain complex logic or decisions.

## Coding Conventions

### C++ Style

- **Indentation**: Use 4 spaces for indentation. Avoid tabs.
- **Line Length**: Limit lines to 80 characters where possible.
- **Braces**: Use the following brace style:

  ```cpp
  // Correct
  if (condition) {
      // Code
  } else {
      // Code
  }

  // Incorrect
  if (condition)
  {
  // Code
  }
  else
  {
  // Code
  }

- **Naming:**  
  - Use camelCase for variables and functions (e.g., `playerScore`, `resetBall()`).
  - Use PascalCase for class names (e.g., `Ball`, `Paddle`).

- **Comments:**  
  - Use `//` for single-line comments.
  - Use block comments `/* ... */` for multi-line explanations where needed.

- **File organization:**  
  - Group related functions inside classes.
  - Keep `main()` function clean and delegate logic to classes/methods.

---

Following these guidelines will help keep the **Pong** code readable and maintainable. Thanks for contributing!
