```markdown
# 📘 Assignment: Python Text Processing

## 🎯 Objective

Practice working with strings, file I/O, and text manipulation in Python by building small utilities that process text files.

## 🎯 Learning Objectives

- Parse and transform text using string methods and regular expressions
- Read from and write to files safely using Python file I/O
- Implement functions to count, search, and summarize textual data
- Build small command-line utilities that accept arguments

## 🧭 Prerequisites

- Basic Python programming (variables, control flow, functions)
- Familiarity with the command line (running Python scripts)

## 📝 Tasks

### 🛠️ Task 1 — Word Count Utility

#### Description
Write a script that reads a text file and prints the total number of words, lines, and characters.

#### Requirements

- Accept a file path as input (command-line argument or prompt)
- Correctly count words, lines, and characters
- Handle missing files or read errors gracefully

### 🛠️ Task 2 — Search and Replace

#### Description
Implement a utility that searches for a substring or regex in a file and optionally replaces matches with a replacement string.

#### Requirements

- Support plain substring search and optional regex mode
- Allow replacing all matches and writing output to a new file
- Preserve the original file on replace (write to a new file by default)

### 🛠️ Task 3 — Summary Report

#### Description
Generate a simple summary for a text file: most common words, average word length, and frequency of lines containing a specific keyword.

#### Requirements

- Produce a readable summary printed to the console
- Use a case-insensitive approach for counting words
- Exclude common stopwords (simple list is fine)

## 📁 Provided Files

- No starter code provided. Create your `.py` files in this folder (e.g., `wordcount.py`, `search_replace.py`).

## ▶️ How to run

Examples (run from this assignment folder):

```bash
python3 wordcount.py sample.txt
python3 search_replace.py --file sample.txt --search "old" --replace "new"
```

Adjust filenames and flags according to your implementation.

## 💡 Hints and Tips

- Use the `argparse` module for command-line arguments
- For regex features, use the `re` module with `re.IGNORECASE` when appropriate
- Read files with `with open(...) as f:` to ensure proper closing

## 📅 Due Date

- Due date: 2025-12-25

## ✅ Submission

- Add your `.py` files to this assignment folder and follow instructor submission instructions.

Good luck — explore text processing and have fun! ✨

```
