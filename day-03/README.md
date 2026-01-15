# Day 03 – Treasure Island

## Overview

My third Python program from Angela Yu's course. An interactive text-based adventure game where players navigate through choices to find treasure.

## What I Learned

- **print()** - Displaying output and ASCII art
- **input()** - Getting user input
- **Variables** - Storing user choices
- **String methods** - .lower() for case-insensitive input
- **Conditional logic** - if/elif/else statements
- **Nested conditions** - Multi-level decision making
- **Comparison operators** - == for string comparison
- **Escape characters** - Using backslashes for quotes

## How It Works

1. Displays an ASCII art treasure map
2. Welcomes the player to Treasure Island
3. Presents the first choice: go "left" or "right" at a crossroad
4. If left: Second choice - "wait" for a boat or "swim" across the lake
5. If wait: Third choice - pick a door color (red, yellow, or blue)
6. Different choices lead to different outcomes:
   - Yellow door: You win and find the treasure!
   - Red door: Game Over (fire room)
   - Blue door: Game Over (beasts room)
   - Wrong choices at any step lead to Game Over

## Run

```bash
python task.py
```
