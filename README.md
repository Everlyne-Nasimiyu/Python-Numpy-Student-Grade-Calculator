# Student Grade Calculator

## Overview
This Python script utilizes the `numpy` library to efficiently calculate and display student grades based on their marks in multiple subjects. It's an interactive command-line tool that allows users to input the number of students, subjects, and their respective marks, then generates a tabular grade report.

## Features
-   **Interactive Input**: Guides the user through entering the number of students, subjects, and marks for each.
-   **NumPy Powered**: Leverages `numpy` arrays for efficient numerical operations like summing marks and calculating percentages.
-   **Grade Calculation**: Automatically assigns grades (A+, A, B+, B, C, F) based on predefined percentage ranges.
-   **Tabular Report**: Presents a clear and well-formatted grade report including student name, total marks, percentage, and assigned grade.
-   **Multiple Runs**: Allows the user to calculate grades for multiple sets of students without restarting the script.

## How to Run

### Prerequisites
Make sure you have Python and NumPy installed.

```bash
pip install numpy
```

### Execution
1.  Save the provided Python code as a `.py` file (e.g., `grade_calculator.py`).
2.  Open your terminal or command prompt.
3.  Navigate to the directory where you saved the file.
4.  Run the script using the Python interpreter:

    ```bash
    python grade_calculator.py
    ```

5.  Follow the on-screen prompts to enter the required information.

## Example Usage

```
Enter the number of students: 3
Enter the number of subjects: 2

Enter the marks of each student in each subject (out of 100):
Enter marks for Student 1, Subject 1: 67
Enter marks for Student 1, Subject 2: 88
Enter marks for Student 2, Subject 1: 90
Enter marks for Student 2, Subject 2: 78
Enter marks for Student 3, Subject 1: 67
Enter marks for Student 3, Subject 2: 88

-----Student Grade Report-----
| Student Name    | Total Marks  | Percentage   | Grade    |
|-----------------|--------------|--------------|----------|
| Student 1       | 155.00       | 77.50      % | B+       |
| Student 2       | 168.00       | 84.00      % | A        |
| Student 3       | 155.00       | 77.50      % | B+       |
------------------------------------------------------------------

Do you want to calculate grades for more students? (yes/no): no
Thank you for using the Grade Calculator. Goodbye!
```

## Technologies Used
-   Python
-   NumPy

## Contributing
Feel free to fork this repository, suggest improvements, or report issues. 
