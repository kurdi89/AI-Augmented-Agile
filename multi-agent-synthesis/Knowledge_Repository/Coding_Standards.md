# Coding Standards

This document outlines the coding standards and best practices to be followed by all Developer Agents. Adherence to these standards is mandatory and will be enforced through automated linting and code reviews.

## 1. General Principles

- **Clarity:** Code should be clear, readable, and easy to understand.
- **Simplicity:** Prefer simple, straightforward solutions over complex ones (KISS).
- **Consistency:** Code should be consistent with the existing style of the codebase.

## 2. Naming Conventions

- **Variables:** Use `camelCase` for variable names (e.g., `let myVariable`).
- **Functions:** Use `camelCase` for function names (e.g., `function myFunction()`).
- **Classes:** Use `PascalCase` for class names (e.g., `class MyClass {}`).
- **Constants:** Use `UPPER_CASE_SNAKE_CASE` for constants (e.g., `const MY_CONSTANT`).

## 3. Formatting

- **Indentation:** Use 2 spaces for indentation. Do not use tabs.
- **Line Length:** Maximum line length is 120 characters.
- **Semicolons:** Always use semicolons at the end of statements.

## 4. Comments

- Use comments to explain *why* something is done, not *what* is being done. The code itself should explain the "what."
- Use `//` for single-line comments and `/* ... */` for multi-line comments.

## 5. Language-Specific Guidelines

### JavaScript / TypeScript
- Use `let` and `const` instead of `var`.
- Prefer arrow functions `() => {}` where appropriate.
- Use strict equality `===` and `!==` instead of `==` and `!=`.
