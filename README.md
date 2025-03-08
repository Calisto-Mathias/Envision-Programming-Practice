# Student Management System Assignment
## Overview

This assignment is designed to help you practice object-oriented programming (OOP) concepts and memory management using pointers in C++. The task involves creating a menu-driven program to manage a list of students, including adding new students and processing their grades. Additionally, the program should be able to store and retrieve data from a file.

## Prerequisites

Before starting this assignment, ensure you have completed the following topics:

- **Basic C++ Programming**: Understand variables, data types, control structures, functions, and basic operators.
- **Object-Oriented Programming (OOP) Concepts**: Familiarize yourself with encapsulation, abstraction, inheritance, and polymorphism.
- **Pointers and Memory Management**: Understand how to use pointers, dynamic memory allocation (`new` and `delete`), and basic error handling.

## Requirements

### Program Functionality

1. **Student Class**: Create a `Student` class with the following attributes:
   - `name`: A string to store the student's name.
   - `rollNumber`: An integer to store the student's roll number.
   - `grades`: An array or vector of floats to store the student's grades in different subjects (e.g., Math, Science, English).

2. **Menu-Driven Interface**: Implement a menu-driven interface that allows you to:
   - **Add New Student**: Prompt the user to input a student's details and add them to the list.
   - **Display All Students**: Display the details of all students in the list.
   - **Process Grades**: Allow users to input grades for a specific student and calculate the average grade.
   - **Save to File**: Save the list of students to a file.
   - **Load from File**: Load the list of students from a file.
   - **Exit**: Exit the program.

3. **Memory Management**: Use pointers to dynamically allocate memory for each student object. Ensure proper memory deallocation when removing students or exiting the program.

4. **Error Handling**: Implement basic error handling to handle invalid inputs (e.g., non-numeric input when expecting numbers).

### File Handling

- Use a text file (e.g., `students.txt`) to store student data.
- Each line in the file should represent a student's details in a format like: `name,rollNumber,grade1,grade2,grade3`.

### Directory Structure

Organize your project into the following directories:

- **included**: Place all header files (`.h` or `.hpp`) here.
- **src**: Place all source files (`.cpp`) here.
- **build**: Compile your program to output executables in this directory.

### Submission Guidelines

- Ensure your code is well-structured and follows good coding practices.
- Use meaningful variable names and include comments to explain your logic.
- Submit your code as a zip file containing the `included`, `src`, and `build` directories.
- Include a brief report explaining how you implemented the requirements and any challenges you faced.

## Importance of This Assignment

Please note that your performance in this assignment might influence how future work is allocated. As C++ is being used extensively in our project, demonstrating a strong grasp of its concepts will be beneficial. However, we might just be trying to keep you on your toes as well xD and this might not be considered!

## Additional Tips

- Use `std::vector` or dynamic arrays for storing grades if needed.
- Consider using `std::fstream` for file operations.
- Test your program thoroughly with different inputs and scenarios.
