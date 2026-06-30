# AIOPS-JOURNEY-
# Day 4: Introduction to Bash Scripting

Today I learned how to automate multiple Linux commands using a Bash Script.

### Key Concepts:
- **Shebang (`#!/bin/bash`)**: The first line of a script that tells the OS to use the Bash shell interpreter.
- **`echo`**: Used to print text outputs on the terminal interface.
- **`.sh` Extension**: Standard file extension for Linux shell scripts.

### Script Created (`myscript.sh`):
```bash
#!/bin/bash
echo "Hello Nafees Bhai!"
date
pwd

 Day 5: Bash Variables and Dynamic User Input

Today, I moved from static scripting to dynamic scripting by implementing variables and user inputs.

### Core Concepts:
- **Variables**: Containers used to store temporary data (e.g., `USER_NAME`).
- **`read` Command**: Halts script execution to capture interactive inputs from the user terminal.
- **Interpolation (`$`)**: Utilizing the dollar sign to call and print the stored value of a variable inside strings.
