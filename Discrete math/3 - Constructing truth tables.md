# Walk-through
- Rows
	- Number of rows: 2^propositions
- Columns
	- For each propositional variable.
	- For each expression in the compound proposition.
	- For the final compound proposition (Usually at right-end)
- Order of operations:
	- Negation
	- Conjunction
	- Disjunction
	- Implication
	- Biconditional

## Example - 1
Construct a truth table for p ∨ q → ¬r

| p | q | r | p ∨ q | ¬r | p ∨ q → ¬r |
| ---- | ---- | ---- | ---- | ---- | ---- |
| T | T | T | T | F | F |
| T | T | F | T | T | T |
| T | F | T | T | F | F |
| T | F | F | T | T | T |
| F | T | T | T | F | F |
| F | T | F | T | T | T |
| F | F | T | F | F | T |
| F | F | F | F | T | T |

## Example - 2
Construct a truth table for $(p\vee\neg q)\to(p\wedge q)$

| p | q | ¬q | p ∨ ¬q | p ∧ q | $(p ∨ ¬q) → (p ∧ q)$ |
| ---- | ---- | ---- | ---- | ---- | ---- |
| T | T | F | T | T | $T$ |
| T | F | T | T | F | $F$ |
| F | T | F | F | F | $T$ |
| F | F | T | T | **F** | $F$ |
