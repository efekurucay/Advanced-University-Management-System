# About
This project was created as part of an assignment or coursework for CSE102 Computer Programming. As a first-year Computer Engineering student, I developed this project to enhance my skills in software development and algorithm design.

If you're reviewing this project, your feedback or suggestions would be greatly appreciated. Thank you!

# Advanced University Management System

This project simulates a simple university management system. It is used to manage student records and grades.

## Features

- Add student
- Enter grades
- View student information
- List all students
- Automatically calculate grade average
- Determine letter grade

## Usage

When the program is run, the desired operation is selected from the menu:

1. Add Student: Creates a new student record
2. Enter Grade: Adds a grade to an existing student
3. View Student Information: Shows the details of a single student
4. List All Students: Lists all registered students
5. Exit: Terminates the program

## Technical Details

- Developed with Java 8
- Can be compiled using Maven
- Takes user input from the console
- Holds 5 course grades for each student
- Grades must be between 0-100

## Compile and Run

```bash
mvn clean compile
mvn exec:java -Dexec.mainClass="com.university.Main"
```

## Author

Yahya Efe Kuruçay
