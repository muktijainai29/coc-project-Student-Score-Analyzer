 Score Analyzer

A simple C program that analyzes student scores by calculating the average, maximum, and minimum values from user input.

 Features

- Accepts scores for a user-defined number of students
- Calculates:
  - Average score
  - Highest score
  - Lowest score
- Displays a summary report

 Requirements

- C compiler (e.g., GCC)
- Compatible with C99 or later

 How to Compile and Run

Compile:
gcc -o score_analyzer score_analyzer.c

Run:
./score_analyzer

 Program Flow

1. Prompt user for the number of students
2. Collect scores for each student
3. Compute:
   - Average score using computeAvg()
   - Maximum score using extractMaximum()
   - Minimum score using extractMinimum()
4. Display the analysis report

 File Structure

score_analyzer.c   # Main source code
README.md          # Documentation

 Notes

- Input validation is minimal; ensure scores are integers and the number of students is positive.
- For portability and safety, dynamic memory allocation is recommended over variable-length arrays.
- Sample Output

 Score Analyzer is being  Initialized
Enter the number of student for which scores are to process: 3
Enter score for student 1: 78
Enter score for student 2: 85
Enter score for student 3: 92

 Analysis Report:
Average Score: 85.00
Top Score: 92
Lowest Score: 78

📞 Contact

For questions or suggestions, feel free to reach out via GitHub Issues or email.
