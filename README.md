# CODTECH-Task-2
Student Grade Tracker Java Program Overview

Program Name: StudentGradeTracker

![image](https://github.com/user-attachments/assets/f3738ea9-0c46-47f8-987f-02b4bc74a2ac)


Purpose: To develop a Java program that allows users to track and manage student grades, calculating average grades and displaying overall grades with additional information.

Features:

1. Input grades for multiple subjects or assignments
2. Calculate average grade
3. Display overall grade
4. Display letter grade (A-F)
5. Display GPA (4.0 scale)
6. Store and retrieve student information
7. Option to add, update, or delete student records

Program Structure:

1. Student class (represents individual student)
    - Attributes: name, ID, grades (HashMap)
    - Methods: addGrade(), updateGrade(), deleteGrade(), calculateAverage()
2. GradeTracker class (manages student records)
    - Attributes: students (ArrayList)
    - Methods: addStudent(), updateStudent(), deleteStudent(), displayStudentInfo()
3. Main class (program entry point)
    - Creates GradeTracker instance
    - Provides user interface (menu-driven)

User Interface:

1. Main Menu
    - Add Student
    - Update Student
    - Delete Student
    - Display Student Info
    - Calculate Average Grade
    - Exit
2. Input Forms
    - Student name and ID
    - Subject/Assignment name and grade
3. Output Displays
    - Student information
    - Average grade
    - Letter grade
    - GPA

Calculations:

1. Average grade: sum of grades / number of grades
2. Letter grade:
    - A: 90-100%
    - B: 80-89%
    - C: 70-79%
    - D: 60-69%
    - F: below 60%
3. GPA:
    - A: 4.0
    - B: 3.0
    - C: 2.0
    - D: 1.0
    - F: 0.0

Error Handling:

1. Invalid input handling (e.g., non-numeric grades)
2. Student not found handling

Code Organization:

1. Separate classes for Student and GradeTracker
2. Clear and concise method names
3. Proper commenting and documentation

This overview provides a solid foundation for developing a comprehensive student grade tracking program in Java.
