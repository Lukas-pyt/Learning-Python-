# Character Creator (Python)

This is a small Python program that creates a simple text-based RPG character with three attributes.

The program checks whether the input is valid and then prints a formatted character stat block using dots to visualize the stats.

## Features

* Validates the character name
* Ensures stats are integers between 1 and 4
* Requires a total of **7 stat points**
* Displays the stats visually using dots

Example attributes:

* **STR** – Strength
* **INT** – Intelligence
* **CHA** – Charisma

## Example Output

```
res
STR ●●●●○○○○○○
INT ●●○○○○○○○○
CHA ●○○○○○○○○○
```

## How it Works

The function:

```
create_character(name, strength, intelligence, charisma)
```

* validates the inputs
* ensures the rules are followed
* generates a formatted stat block

If the input is invalid, the program returns an error message.

## Example Usage

```python
print(create_character("res", 4, 2, 1))
```

## Purpose

This project was created while learning the **basics of Python**, including:

* functions
* input validation
* conditionals
* string formatting
* simple program structure
