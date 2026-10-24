# Week 6 Assignment: Safe Functions

This assignment practices Python error handling using `try` and `except` to prevent a program from crashing when expected errors occur.

## Files

- `safe_tools.py` — Contains the `safe_divide`, `safe_number`, and `get_field` functions, with test cases for each function.
- `README.md` — Describes the assignment, its files, and why an `if` check alone cannot catch invalid integer conversions.
- `screenshot.png` — Shows the program running with the expected output.

## Why can't an if check catch "abc" on its own?

An `if` check can test a condition, such as whether a string is empty, but it does not automatically catch errors raised when converting text to an integer. Converting `"abc"` using `int()` raises a `ValueError`, which can be handled using `try` and `except`.