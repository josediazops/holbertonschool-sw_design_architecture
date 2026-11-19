# Introduction to Design Patterns with Python

A design pattern is a reusable way to organize code and to solve recurring design problems. A pattern is not a finished implementation to copy mechanically. Instead, it describes a structure of responsibilities and interactions that has proven useful in many systems.

## Factory Pattern

The objective of the task is to extend an existing factory registry to support a new vehicle type, without modifying the core creation logic inside `create`. The registry approach solves this by allowing new types to be registered from outside the core logic. As a result, the `create` function never needs to change.

## Files

| File | Description |
|------|-------------|
| `0-factory.py` | Factory registry extended with a Scooter vehicle type. |

## How to run

```bash
python3 0-factory.py
```

## Author

- Jose A. Diaz
