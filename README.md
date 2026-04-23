# Password Strength Checker (Python)

## Overview
This project is a Python-based password strength checker that evaluates the security level of a user-entered password using pattern matching and rule-based validation.

It provides both a strength rating and actionable feedback to improve password robustness.

## Features
- Checks password length (minimum 8 characters)
- Validates presence of:
  - Lowercase letters
  - Uppercase letters
  - Numbers
  - Special characters
- Classifies passwords as:
  - Weak
  - Moderate
  - Strong
- Provides suggestions for improvement

## Technologies Used
- Python
- Regular Expressions (`re` module)

## How It Works
The program evaluates the password against multiple criteria:
- Each satisfied condition increases the score
- Based on the score, the password strength is determined
- Missing criteria are returned as feedback to the user

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/password-checker.git
