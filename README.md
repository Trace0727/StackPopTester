# StackPopTester

A focused Java project designed to test the behavior of the `Stack.pop()` method using both automated JUnit tests and a manual console-based demo, providing clear insight into stack operations and exception handling in Java.

---

## Project Structure

```
StackPopTester/
├── src/
│   └── StackPopDemo.java
├── test/
│   └── StackPopTest.java
```

---

## Core Java Classes

### `StackPopDemo.java`
A manual console-based driver:
- Demonstrates core `Stack` operations like `push()`, `pop()`, and `peek()`.
- Prints stack changes in sequence to show LIFO behavior.
- Intentionally triggers and catches `EmptyStackException` when attempting to pop from an empty stack.
- Ideal for visually verifying stack behavior during execution.

### `StackPopTest.java`
A JUnit 5 test class for verifying the correctness of the `pop()` method:
- Tests popping from an empty stack (expects an exception).
- Pushes elements into the stack and ensures the top value is returned by `pop()`.
- Covers boundary cases: max size, one less, and one more than the defined limit.
- Uses assertions (`assertEquals()`, `assertThrows()`) to ensure proper behavior.

---

## Future Enhancements
- Add parameterized test cases to reduce redundancy and increase test coverage.
- Expand test suite to include `peek()`, `search()`, and `empty()` methods.
- Create a GUI interface to visualize the stack operations in real time.
- Package project using Maven or Gradle for dependency and test management.

---

## License
This project is licensed for educational and personal use only. Redistribution or modification without permission is prohibited.  
See the [LICENSE] file for full details.

---

## Author
**Trace Davis**  
- GitHub: https://github.com/Trace0727  
- LinkedIn: https://www.linkedin.com/in/trace-d-926380138/
