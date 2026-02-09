# Day 05 – Caesar Cipher

## Overview
My fifth Python program from Angela Yu's course. A classic Caesar Cipher encryption/decryption tool that shifts letters in the alphabet to encode or decode secret messages, complete with ASCII art logo.

## What I Learned
- **`from ... import`** – Importing specific variables from another module
- **Functions with parameters** – Defining reusable functions with multiple arguments (`def caesar(original_text, shift_amount, encode_or_decode)`)
- **Keyword arguments** – Calling functions with named parameters for clarity
- **`for` loop** – Iterating over each character in a string
- **Lists** – Storing the entire alphabet in a list for index-based lookups
- **`.index()`** – Finding the position of an item in a list
- **Modulo operator (`%`)** – Wrapping around the alphabet when shifting past 'z'
- **`+=` operator** – Building strings by concatenation
- **`.lower()`** – Converting user input to lowercase
- **`.isalpha()`** – Validating that input contains only letters
- **f-strings** – Formatting output with embedded expressions
- **Conditional logic** – `if` statements for switching between encode/decode and input validation

## How It Works
1. Displays the Caesar Cipher ASCII art logo
2. Asks the user to choose between **encode** (encrypt) or **decode** (decrypt)
3. Prompts the user to type a message (letters only)
4. Validates input — rejects numbers, symbols, and spaces
5. Asks for a **shift number** to determine how many positions each letter moves
6. Shifts each letter forward (encode) or backward (decode) in the alphabet
7. Wraps around using modulo so shifts beyond 'z' loop back to 'a'
8. Displays the encoded or decoded result

## Run
```
python main.py
```
