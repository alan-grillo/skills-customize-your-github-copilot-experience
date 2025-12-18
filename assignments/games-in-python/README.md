```markdown
# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build the classic Hangman word-guessing game in Python to practice string manipulation, control flow, and user interaction.

## 🎯 Learning Objectives

- Work with strings and lists in Python
- Use loops and conditionals to control game flow
- Read from and use a predefined word list
- Validate and process user input

## 🧭 Prerequisites

- Basic Python knowledge: variables, lists, loops, conditionals, functions
- Python 3 installed (tested with Python 3.8+)

## 📝 Tasks

### 🛠️ Task 1 — Core Hangman Gameplay

#### Description
Implement the core Hangman game loop where the program:

- Selects a random secret word from a predefined list
- Prompts the player to guess one letter at a time
- Reveals correctly guessed letters in their positions
- Tracks and displays remaining incorrect attempts
- Ends when the word is fully guessed or attempts run out

#### Requirements
Completed program should:

- Randomly select words from a predefined list
- Accept single-letter guesses and ignore repeated guesses
- Show current progress using underscores and revealed letters (e.g., `_ a _ _ m a n`)
- Track incorrect guesses and remaining attempts
- Display clear win or lose messages and reveal the secret word on loss

### 🛠️ Task 2 — Enhancements (Optional / Extra Credit)

#### Description
Add one or more enhancements to make the game more robust or fun.

#### Suggested Enhancements

- Load words from an external file (e.g., `words.txt`) or `data.csv`
- Add difficulty levels that change allowed attempts or word length
- Support guessing the full word as an action
- Keep a simple high-score or statistics across rounds

## 📁 Provided Files

- `starter-code.py` — a starter script to help you begin (see the assignment folder)

## ▶️ How to run

Run the game from the command line in the assignment folder:

```bash
python3 starter-code.py
```

If your solution is in a different file, replace `starter-code.py` with your filename.

## 💡 Hints and Tips

- Validate input: accept only single alphabetic characters for letter guesses
- Keep track of guessed letters to prevent duplicate processing
- Use `random.choice()` from the `random` module to pick a word

## 📅 Due Date

- Original due date: 2025-11-17

## ✅ Submission

- Submit your completed `.py` file(s) in this assignment folder or follow instructor submission instructions.

Good luck — have fun building your Hangman game! :rocket:

```

# 🎮 Hangman Game Challenge

Build the classic word-guessing game using Python strings, loops, and user input.

## � What You'll Build

Create a Hangman game where players guess letters to reveal a hidden word before running out of attempts.

**Skills practiced:** String manipulation, loops, conditionals, random selection

## ✅ Must Have's

Your game must:
- Randomly select words from a predefined list
- Accept letter guesses and show current progress (_ _ _ format)
- Track incorrect guesses remaining
- End when word is guessed or attempts exhausted
- Display win/lose messages
