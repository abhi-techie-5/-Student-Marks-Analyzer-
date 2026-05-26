# -Student-Marks-Analyzer-


A Python-based project that analyzes student marks using NumPy and displays important statistics such as total marks, average marks, highest marks, lowest marks, and grades.

## Project Overview

The **Student Marks Analyzer** is a beginner-friendly Python project designed to help understand how arrays, functions, loops, and conditional statements work together in a real-world application.

The program takes marks of multiple students as input and performs statistical analysis using the NumPy library.

## Features

* Take marks input for multiple students
* Store marks using NumPy arrays
* Calculate:

  * Total marks
  * Average marks
  * Highest marks
  * Lowest marks
* Automatically assign grades
* Display fail/pass status
* Simple and interactive console-based execution

## Technologies Used

* Python 3
* NumPy
* Jupyter Notebook

## Project Structure

```bash
project2.ipynb   # Main project notebook
```

## How the Project Works

### Step 1: User Input

The program asks the user to enter the number of students and their marks.

### Step 2: Store Data

Marks are stored inside a NumPy array for efficient numerical operations.

### Step 3: Statistical Analysis

The project calculates:

* Sum of all marks
* Average marks
* Maximum marks
* Minimum marks

using NumPy functions like:

```python
np.sum()
np.mean()
np.max()
np.min()
```

### Step 4: Grade Evaluation

Grades are assigned based on marks:

| Marks Range  | Grade |
| ------------ | ----- |
| 85 and above | A     |
| 70 - 84      | B     |
| 50 - 69      | C     |
| Below 50     | Fail  |

## Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/your-repository-name.git
```

### Move into the Project Folder

```bash
cd your-repository-name
```

### Install Required Library

```bash
pip install numpy
```

## Run the Project

### Using Jupyter Notebook

```bash
jupyter notebook
```

Open `project2.ipynb` and run all cells.

## Example Output

```text
Enter the number of students: 3
Enter the marks for student1: 90
Enter the marks for student2: 76
Enter the marks for student3: 45

Sum of all marks is given as: 211
Average marks is given as: 70.33
Highest marks is given as: 90
Lowest marks is given as: 45

Grade of student 1 is A
Grade of student 2 is B
student 3 is Fail!
```

## Learning Outcomes

This project helps in understanding:

* Python functions
* Loops and conditions
* NumPy arrays
* Statistical calculations
* User input handling
* Data analysis basics
* Problem-solving using Python

## Future Improvements

* Add graphical user interface (GUI)
* Store student records in files or databases
* Add subject-wise analysis
* Generate report cards
* Add data visualization using Matplotlib
* Export results to Excel or PDF

## Important Concepts Used

* Functions
* Conditional statements
* Loops
* Arrays
* Statistical operations
* Data processing
* Console application development

## Author

Created by Abhishek

## License

This project is open-so
