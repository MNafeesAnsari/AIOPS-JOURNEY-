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

# Day 6: Decision Making with If/Else Statements

Today, I introduced logical decision-making components into my Bash scripts using conditional If/Else control structures.

### Key Learnings:
- **`if [ condition ]`**: Syntax to evaluate logical assumptions. Spaces inside brackets are mandatory in Bash.
- **`then` & `else`**: Branches that dictate separate outputs based on whether the condition returns True or False.
- **`fi`**: The mandatory concluding tag used to terminate a conditional block in Linux scripting.

# Day 7: Automation with For Loops

Today, I mastered task repetition and loop structures in Bash scripting to automate bulk operations.

### Key Learnings:
- **`for i in {1..5}`**: Defines a range-based loop that iterates exactly 5 times.
- **`do` & `done`**: The code blocks that enclose the operations to be executed on each loop iteration.
- **`sleep 1`**: Introduces a controlled delay inside execution streams, useful for rate-limiting scripts or managing cron jobs.


# Day 8: Reusability with Bash Functions

Today, I advanced my scripting skills by introducing functions to write modular, clean, and production-grade shell scripts.

### Key Learnings:
- **Functions**: Named blocks of code designed to perform a specific task. They prevent code duplication (DRY principle: Don't Repeat Yourself).
- **Encapsulation**: Grouping monitoring utilities like `uptime` and `whoami` inside a single executable functional unit.
- **Calling Structure**: Invoking a function simply by writing its name inside the execution path of the script.
