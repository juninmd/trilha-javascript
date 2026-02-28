# AGENTS.md File Guidelines

These guidelines are designed to ensure consistent, maintainable, and high-quality code development within the AGENTS repository. Adherence to these principles is crucial for a successful and robust project.

## 1. DRY (Don't Repeat Yourself)

*   All functions, classes, and methods must have single, clear responsibilities.
*   Avoid duplicating logic. Refactor existing code to reduce redundancy.
*   When a feature is implemented, it should be encapsulated within a dedicated module or component.

## 2. KISS (Keep It Simple, Stupid)

*   Prioritize readability and understandability.
*   Use the simplest possible solution for a given task.
*   Avoid unnecessary complexity.
*   Strive for clarity in your code's structure and naming.

## 3. SOLID Principles

*   **Single Responsibility Principle:** Each class/module should have one, and only one, reason to change.
*   **Open/Closed Principle:**  The system should be extensible without modifying the existing code.  New functionality should be added through new classes/modules, not by modifying the core.
*   **Liskov Substitution Principle:**  Subclasses should be substitutable for their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:** Clients should not be required to establish dependencies with objects they do not use.
*   **Dependency Inversion Principle:** High-level modules should not depend on low-level modules; they should depend on abstractions.

## 4. YAGNI (You Aren't Gonna Need It)

*   Avoid adding features or logic that are not currently required.
*   Focus on delivering working functionality first.
*   Don’t implement features prematurely.

## 5. Code Style & Formatting

*   **Indentation:** Use 2 spaces for indentation.
*   **Line Length:**  Maximum 120 characters per line.
*   **Naming Conventions:** Follow established naming conventions (e.g., snake_case for functions/classes).  Document variable and function names clearly.
*   **Comments:**  Provide clear, concise, and helpful comments explaining *why* the code is written, not *what* it does (unless the logic is exceptionally complex).  Keep comments focused.
*   **Whitespace:**  Use whitespace consistently to enhance readability.

## 6. File Size & Structure

*   **Maximum File Size:** 180 lines of code total.  (excluding comments and imports).
*   **File Structure:** Organize files into logical categories with well-defined directory structures.  Use a consistent naming convention within each file.  Consider a modular structure where files represent distinct components of the AGENTS system.
*   **Documentation:** Include brief, helpful documentation for each file/module, explaining its purpose and inputs/outputs.  (Use JSDoc style comments for improved IDE support).

## 7. Test Coverage Requirements

*   **Minimum:** 80% of code should be covered by automated tests.
*   **Test Type:** All unit tests should be written.
*   **Test Focus:** Tests should cover critical logic, boundary conditions, and error handling.
*   **Test Drivers:**  Test drivers should be written to isolate specific components and ensure their correct behavior.

## 8.  Development Practices

*   **Code Reviews:** All changes must be reviewed by at least one other developer before being merged.
*   **Version Control:** Use Git for version control.
*   **Testing:**  All code should be thoroughly tested using unit tests.
*   **Error Handling:**  Implement robust error handling and logging.

## 9.  Specific Guidelines (Example - Modify as needed)

*   **Data Structures:**  Use appropriate data structures for each task. Consider immutability where appropriate.
*   **Algorithms:** Favor efficient algorithms.
*   **Error Handling:** Implement comprehensive error handling with informative error messages.
*   **Concurrency:** Consider concurrency considerations when designing and implementing AGENTS functionality.  (This is a high priority, but requires careful consideration).


These guidelines are intended as a starting point and will be updated as the AGENTS repository evolves. Continuous improvement and adherence to these principles will contribute to the quality and maintainability of the system.