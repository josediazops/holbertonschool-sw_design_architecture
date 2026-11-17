# Introduction to UML Modeling

This project introduces UML (Unified Modeling Language) as a tool to represent software systems. It uses a Library Loan System as the example problem.

## Task 0: Class Diagram

Create a UML class diagram using Mermaid syntax to represent the Library Loan System.

### Requirements

- Identify the required classes, attributes, and methods.
- Represent relationships and multiplicities.
- Use the exact names from the project description.
- Use Python-style data types.
- Submit the diagram in Mermaid format.

## Task 1: Sequence Diagram

Create a Mermaid sequence diagram that models how objects interact when a user borrows a book.

### Requirements

- Incude all relevant participants.
- Follow the required order of interactions.
- Use method names exactly as described in the problem statement.
- Declare only `User`, `Library` and `Book` at the beginning.
- Create `Loan` with `create participant Loan` when it is created.
- End with `Library-->>User: loan created`.

## Files

| File | Description |
|------|-------------|
| `0-class_diagram.mmd` | Mermaid class diagram of the Library Loan System |
|`1-sequence_diagram.mmd` | Mermaid sequence diagramof a user borrowing a book |
|
## Environment

- Ubuntu 20.04
- Mermaid-compatible renderer

## Author

Jose Diaz