# GitHub Copilot Instructions

## File Exclusions

When analyzing the workspace or performing tasks, do not read or use the contents of:
- `.ipynb` files (Jupyter notebooks)
- `.py` files (Python scripts)

These files contain puzzle solutions and should not be used as context for code generation or analysis tasks. The exception to this is reading your own code when you are the author of the file.

## Solution Guidelines

When working on solutions to `puzzle.txt` files:
- Always create solutions in a new `.ipynb` (Jupyter notebook) file
- Document your work using markdown cells throughout the notebook to explain:
  - Problem understanding and approach
  - Key insights or algorithms used
  - Step-by-step explanations of the solution logic
  - Any challenges encountered and how they were resolved
- There will be a test case file associated with each puzzle; ensure your solution passes all provided test cases called `test.txt` and 
the puzzle input called `input.txt`

## Environment Guidelines

- Never suggest creating or using virtual environments (venv, virtualenv, conda, etc.)
- Work with the existing Python environment in the dev container
