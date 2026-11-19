# Introduction to Design Patterns with Python

A design pattern is a reusable way to organize code and to solve recurring design problems. A pattern is not a finished implementation to copy mechanically. Instead, it describes a structure of responsibilities and interactions that has proven useful in many systems.

## Factory Pattern

The objective of the task is to extend an existing factory registry to support a new vehicle type, without modifying the core creation logic inside `create`. The registry approach solves this by allowing new types to be registered from outside the core logic. As a result, the `create` function never needs to change.

## File

| File | Description |
|------|-------------|
| `0-factory.py` | Factory registry extended with a Scooter vehicle type. |


## How to run

```bash
python3 0-factory.py
```


## Observer - Adding a new subscriber

The objective is to implement a new observer and subscribe it to a running notification system. Filtering it to receive only specific event topics.

## File

| File | Description |
| `1-observer.py` | Observer pattern extended with an SMS subcriber for breaking news. |

## How to run

```bash
python3 1-observer.py
```


##  Decorator - Adding a new wrapper

The objective is to add a new decorator that extends `Beverage` by wrapping it, composing correctly with existing decorators without modifying any existing class.

## File

| File | Description |
| `2-decorator.py` | Decorator pattern extended with a new beverage wrapper for the coffeeshop. |