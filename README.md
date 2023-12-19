# python-black-pre-commit
A Python code formatter using black and isort as pre-commit hooks

Git Pre-Commit Hook for Python Formatting
This is a git pre-commit hook script that automatically formats Python code using [black] and [isort] before committing. The script runs black and isort on the changed files and checks if they are compliant with the [PEP 8] style guide. If any file is not formatted correctly, the commit will be aborted and the script will show the diff and the errors.

Why use this script?
This script is a simple and convenient way to ensure that your Python code is consistent, readable, and follows the best practices. By using this script, you can avoid committing code that does not meet your standards, and save time and effort in code review and debugging.

How to use this script?
To use this script in your project, you need to do the following steps:

1. Copy the pre-commit file from this repository to the .git/hooks directory in your project.
2. Make sure the pre-commit file is executable. You can use the command chmod +x .git/hooks/pre-commit to do so.
3. Install black and isort on your system. You can use pip, conda, or other methods. See the [black installation instructions] and the [isort installation instructions] for more details.


That's it! Now, every time you commit some changes, the script will run black and isort and format your code. If any file is not formatted correctly, the commit will be aborted and you will see an error message explaining what went wrong. You can fix the issues and try again, or skip the script by using git commit --no-verify (not recommended).

How to contribute?
If you want to contribute to this project, you are welcome to do so. Please follow the contribution guidelines and make sure your code passes the script before submitting a pull request.
