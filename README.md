# TLEP Python Lab Exercises

This folder contains 16 independent Python programs corresponding to the lab exercises shown in the supplied TLEP checklist. Each exercise is saved as a separate `.py` file and numbered in the same order as the checklist.

## Program index

| File | Lab exercise | Module |
|---|---|---|
| program 1 | Basic Python programs (variables, operators, input/output) | I |
| program 2 | Simple calculator | I |
| program 3 | Area calculation | I |
| program 4 | Number guessing game | II |
| program 5 | Prime number program | II |
| program 6 | Factorial program | II |
| program 7 | Fibonacci series using recursion | II |
| program 8 | Contact book using lists and dictionaries | III |
| program 9 | Student grading system | III |
| program 10 | Frequency counter using dictionaries | III |
| program 11 | Log file reader program | IV |
| program 12 | Student data manager using files | IV |
| program 13 | CSV-based payroll management system | IV |
| program 14 | Bank account system using OOP | V |
| program 15 | Library management system | V |
| program 16 | Dice simulator using random module | V |

## Requirements

- Python 3.8 or later is recommended.
- No third-party packages are required. All programs use Python's standard library.

## How to run

1. Extract the ZIP file.
2. Open a terminal or command prompt in the extracted folder.
3. Run the program you want, for example:

   ```bash
   python "program 1 - Basic Python Programs.py"
   ```

   On some systems, use `python3` instead of `python`.

4. Follow the prompts displayed in the terminal.

## Notes

- Every program is standalone. Run one file at a time.
- Programs 11–13 create or read supporting files in the current working directory:
  - Program 11 reads a log file path supplied by the user (default: `sample.log`).
  - Program 12 stores student records in `students.json`.
  - Program 13 stores payroll records in `payroll.csv`.
- The contact book and library programs keep their data in memory while running; their data is reset when the program exits.
- These are educational lab implementations. They are not production-grade financial, payroll, or record-management systems.
