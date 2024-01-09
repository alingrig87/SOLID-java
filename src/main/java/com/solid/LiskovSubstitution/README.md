# Liskov Substitution Principle (LSP)

## Overview

The Liskov Substitution Principle (LSP) is a key principle in object-oriented design that extends the idea of polymorphism. It emphasizes that objects of a superclass should be replaceable with objects of a subclass without affecting the correctness of the program. By adhering to LSP, we ensure that the derived classes maintain the expected behavior of the base classes.

## Principle Explanation

### What is LSP?

LSP extends the idea of polymorphism, stating that objects of a base class should be replaceable with objects of a derived class without altering the correctness of the program. In other words, a derived class should adhere to the contract established by its base class.

### Why is LSP Important?

1. **Polymorphism**: Enables the use of derived classes wherever the base class is expected, enhancing flexibility.
2. **Correctness**: Ensures that substituting objects of derived classes for objects of base classes doesn't break the functionality.
3. **Maintainability**: Facilitates the addition of new classes without disrupting existing code.
