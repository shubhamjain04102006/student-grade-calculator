# Student Grade Calculator

A simple console-based program written in C that calculates a student's total marks, average, letter grade, and pass/fail status based on subject-wise marks entered by the user.

## Features

- Enter marks for multiple subjects (up to 20)
- Calculates total and average marks
- Assigns letter grade (A, B, C, D, F)
- Shows Pass or Fail status
- Basic input validation (rejects values outside 0-100)

## How to Compile and Run

Make sure you have GCC installed.

```bash
gcc grade_calculator.c -o grade_calculator
./grade_calculator
```

## Sample Output

```
=== Student Grade Calculator ===

Enter student name: John
How many subjects? 3
Enter marks for subject 1 (out of 100): 85
Enter marks for subject 2 (out of 100): 76
Enter marks for subject 3 (out of 100): 90

--- Result for John ---
Subjects entered: 3
Total marks: 251.00
Average: 83.67
Grade: B
Status: PASS
```

## Grade Scale

| Marks | Grade |
|-------|-------|
| 90 - 100 | A |
| 80 - 89  | B |
| 70 - 79  | C |
| 60 - 69  | D |
| Below 60 | F |

## Technologies Used

- C Language
- GCC Compiler

## Author

Made by Shubham Jain
