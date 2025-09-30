# Knights and Knaves Logic Puzzle Solver

This project features an AI that solves Raymond Smullyan's classic "Knights and Knaves" logic puzzles. The solution involves translating the puzzle's statements into a formal knowledge base using propositional logic and then running a model-checking algorithm to deduce the identity of each character.

This project was developed as part of Harvard's CS50's Introduction to Artificial Intelligence with Python course.

The program takes the logical premises for each puzzle and outputs the conclusions derived by the model checker.

*(Tip: Run `python puzzle.py`, take a screenshot of the terminal output, and save it as `output.png` in the project folder.)*

## Concepts & Technologies

- **Python**
- **Artificial Intelligence**
- **Propositional Logic:** Translating natural language statements into logical sentences (`And`, `Or`, `Not`, `Implication`, `Biconditional`).
- **Knowledge Representation:** Building a knowledge base (`KB`) that accurately models the puzzle's rules and statements.
- **Model Checking:** Using an algorithm to determine which propositional symbols must be true based on the KB.


This project was developed as part of Harvard's CS50's Introduction to Artificial Intelligence with Python course. The translation of the puzzles into a propositional logic knowledge base was implemented by me, while the model-checking algorithm and logic classes (`logic.py`) were provided by the course.
*Developed by VeetGT.*
