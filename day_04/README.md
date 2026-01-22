# Day 04 – Rock, Paper, Scissors

## Overview

My fourth Python program from Angela Yu's course. A classic Rock, Paper, Scissors game where players compete against the computer with ASCII art visuals.

## What I Learned

- **`import random`** - Importing modules to use random functionality
- **`random.randint()`** - Generating random integers for computer choices
- **`input()`** - Getting user input with type conversion
- **`int()`** - Converting strings to integers
- **Lists** - Storing multiple items (ASCII art) in a collection
- **List indexing** - Accessing items using `[index]`
- **Conditional logic** - `if/elif/else` statements for game logic
- **Comparison operators** - `==`, `>=`, `<` for evaluating conditions
- **Logical operators** - `or` and `and` for complex conditions
- **Multi-line strings** - Using triple quotes for ASCII art

## How It Works

1. Displays three ASCII art options: Rock (0), Paper (1), or Scissors (2)
2. Prompts the user to choose by entering a number (0-2)
3. Shows the user's chosen weapon with ASCII art
4. Computer randomly selects its weapon
5. Displays the computer's choice
6. Determines the winner based on classic rules:
   - **Rock beats Scissors**
   - **Scissors beats Paper**
   - **Paper beats Rock**
   - **Same choice = Draw**
   - **Invalid input = Automatic loss**

## Run

```bash
python task.py
```
