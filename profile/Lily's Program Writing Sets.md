# Lily's Program Writing Sets

A guide to crafting elegant and maintainable code, inspired by the pursuit of software craftsmanship.

## Introduction

This document outlines "Lily's Program Writing Sets" — a collection of guidelines and principles designed to elevate code quality and promote good programming practices. Whether you're a budding developer or a seasoned engineer, these guidelines can serve as a valuable reference to enhance the clarity, correctness, and maintainability of your code.

## Guiding Principles

At the heart of "Lily's Program Writing Sets" lie three fundamental principles:

1. **Clarity:** Code should be easy to read, understand, and reason about, even for those who didn't write it.
2. **Correctness:**  Code should function as intended, be free of errors, and handle unexpected situations gracefully.
3. **Maintainability:**  Code should be structured in a way that makes it easy to modify, extend, and debug over time.

## The Guidelines

These principles manifest in the following specific guidelines, categorized for ease of reference:

### I. Data and Variables

1. **Limit Pointer Use:** Use pointers judiciously, only when they provide a clear advantage, and with robust error checking.
2. **Declare Variables at the Smallest Scope Possible:** Keep variables close to where they are used to minimize side effects and enhance clarity.

### II. Functions

3. **Restrict Function Complexity:**
    - Aim for a Cyclomatic Complexity of 15 or less. Use tools to measure this objectively.
    - Break down complex functions into smaller, more manageable units.
4. **Favor a Manageable Number of Function Parameters:**
    - Minimize the number of parameters passed to a function for better readability.
    - Consider using data structures or objects to group related inputs.
5. **Use Assertions Strategically:**
    - Employ assertions to validate critical assumptions within your code and catch potential errors early.
    - Place assertions thoughtfully; their number should reflect the complexity and criticality of the code.

### III. Control Flow

6. **Use Simple Control Flow Structures:**
    - Avoid complex, hard-to-follow structures like `goto` statements or excessive nesting.
    - Favor clear and straightforward control flow mechanisms (e.g., `if`, `else`, `for`, `while`).

### IV. Code Organization

7. **Code Structure and Organization:**
    - **Minimize Nesting:**
        - **Use Inversion:** Invert conditions to reduce nesting depth.
        - **Merge Related Conditions:** Combine `if` conditions that perform similar checks.
        - **Extract Logic:**  Move nested code into separate functions to improve readability.
    - **Promote Reusability and Clarity:**
        - **Avoid Code Duplication:**  Extract common code blocks into reusable functions or modules.
        - **Use Shared Logic:** Centralize common algorithms or calculations to reduce redundancy.

### V. Naming and Conventions

8. **Apply a Clear and Consistent Naming Convention:**
    - **Universality:** Apply the same convention to all code elements (variables, functions, classes, etc.).
    - **Language Awareness:** Adhere to established conventions of your chosen programming language.
    - **Clarity is Key:** Choose descriptive and meaningful names that clearly convey purpose and functionality.

### VI.  Tools and Practices

9. **Use a Version Control System:** Track changes, collaborate effectively, and safeguard your codebase (e.g., Git).
10. **Write Meaningful Comments:**  Explain the "why" behind your code decisions, not just the "what," to improve understanding and maintainability.

## Continual Improvement

These guidelines are not meant to be rigid rules but rather a starting point for cultivating good coding habits. As you gain experience, adapt and refine these principles to suit your evolving needs and project contexts. Encourage feedback from fellow developers to foster a collaborative culture of code quality.
