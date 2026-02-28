```markdown
# AGENTS.md - Guidelines for AI Coding Agents

These guidelines are designed to ensure the creation and maintenance of high-quality AI coding agents within this repository. Adherence to these principles is mandatory for all development activities.

## 1. DRY (Don't Repeat Yourself)

*   All code, logic, and utility functions should be encapsulated in their own dedicated files.
*   Avoid creating redundant code snippets.
*   When a component needs to be reused, provide a clear and concise way to access and utilize it.
*   Refactor existing code to eliminate duplication of functionality.

## 2. KISS (Keep It Simple, Stupid)

*   Prioritize clarity and readability over unnecessary complexity.
*   Keep functions and classes short and focused.
*   Use meaningful variable and function names.
*   Avoid overly clever or obscure solutions.
*   Ensure functions have single responsibilities.

## 3. SOLID Principles

*   **Single Responsibility Principle:** Each class or function should have one well-defined purpose.
*   **Open/Closed Principle:**  The system should be extensible without modifying its core implementation.  New functionalities should be added through new classes or functions without altering existing code.
*   **Liskov Substitution Principle:**  Subclasses should be substitutable for their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:** Clients should not be forced to depend on methods they do not use.
*   **Dependency Inversion Principle:**  High-level modules should not depend on low-level modules; they should depend on abstractions.

## 4. YAGNI (You Aren't Gonna Need It)

*   Only implement features that are explicitly required for the current task.
*   Avoid adding functionality that is unlikely to be used in the future.
*   Refactor code to remove obsolete or unused elements.
*   Focus on the core requirements; don't over-engineer for potential future needs.

## 5. Code Length & Structure

*   Each file must be no more than 180 lines of code.
*   Use proper indentation to enhance readability.
*   Break down large functions into smaller, more manageable sub-functions.
*   Employ comments judiciously; explain *why* the code is doing something, not *what* it's doing.
*   Consider a clear separation of concerns across multiple files.

## 6. Testability & Coverage

*   All unit tests must be implemented and pass successfully.
*   Unit tests should cover all critical logic.
*   Test cases should be designed to verify expected behavior.
*   Aim for at least 80% test coverage.  Automated test suites should be maintained.
*   Strive for minimal code requiring manual verification.

## 7.  Data Structures & Algorithms

*   Utilize appropriate data structures for efficient processing.
*   Consider time and space complexity when designing algorithms.
*   Employ well-established algorithms where appropriate.

## 8.  Error Handling & Validation

*   Implement robust error handling to gracefully handle unexpected situations.
*   Provide informative error messages to users.
*   Validate user input to prevent malicious or incorrect data.
*   Avoid relying solely on exception handling for all errors.

## 9.  Documentation & Comments

*   Write clear and concise documentation for all functions, classes, and modules.
*   Include API documentation where necessary.
*   Use docstring conventions for improved readability and maintainability.

## 10.  Maintainability & Evolution

*   Design the system with future modifications in mind.
*   Use consistent coding style and naming conventions.
*   Implement version control (e.g., Git) to track changes.
*   Regularly review and refactor code to improve maintainability.

## 11.  Specific File Structure (Examples - Adapt as needed)

*   `agent_core.py`: Contains core agent logic, utilities, and data structures.
*   `agent_state.py`: Manages agent state, providing state management functionalities.
*   `agent_communication.py`: Handles communication protocols and message formats.
*   `agent_data_management.py`: Deals with data storage, retrieval, and validation.
*   `unit_tests/`: Contains all unit test code.
*   `integration_tests/`: Contains integration tests to verify the agent works as a whole.
*   `docs/`: Contains any documentation written here.

These guidelines are intended to serve as a foundation for the development of this AGENTS.md repository.  Continuous improvement and refinement of these practices will be encouraged.
```