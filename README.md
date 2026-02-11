# Course-Management-System-Java-

This project implements an object‑oriented model of a school course in Java. It supports storing student information, tracking exam grades, computing statistics, and managing enrollment. The design focuses on clean class structure, encapsulation, and practical data‑handling methods.

## Features
Add/insert new students into a course

Store each student’s:

Name

ID

Exam grades

Display all students and their grades

Compute the average score for any exam

Determine the lowest exam grade among all students

Fully object‑oriented design using Java classes

## Technical Skills Demonstrated
Object‑oriented programming (OOP)

Class design and encapsulation

Array and/or ArrayList data structures

Method design for:

Aggregation

Searching

Statistical calculations

Input validation and error handling

Clean separation of model and logic


## Class Overview
Student Class
Represents a single student with:

name

id

examGrades[] or ArrayList<Integer>

Methods typically include:

Getters/setters

Display formatting

Access to individual exam scores

Course Class
Stores and manages all students in the course.

Core methods:

addStudent(Student s)

displayStudents()

getExamAverage(int examIndex)

getLowestExamScore(int examIndex)

## How to Run
Clone the repository

Open the project in any Java‑compatible IDE (Eclipse, IntelliJ, VS Code, etc.)

Compile and run Main.java



## Example Output (Optional)
Students in the course:

Student Id: 123-45-6789
Name: Homer Simpson
Exams: 58.7 79.2 68.8 73.4 

Student Id: 765-43-2100
Name: Marge Simpson
Exams: 85.5 79.6 81.8 88.3 

Student Id: 999-99-9999
Name: Lisa Simpson
Exams: 94.8 93.3 97.7 98.2

Student Id: 666-66-6666
Name: Bart Simpson
Exams: 21.5 31.8 44.2 29.7 

Student Id: 317-46-2525
Name: Ned Flanders
Exams: 92.3 91.8 81.7 89.4 

Student Id: 826-55-5551
Name: Ralph Wiggum
Exams: 4.5 8.2 6.1 11.8 

Student Id: 301-33-4412
Name: Selma Bouvier
Exams: 65.3 71.2 58.7 81.1

Student Id: 448-44-5511
Name: Nelson Muntz
Exams: 0.0 0.0 0.0 0.0 

Student Id: 611-66-1234
Name: Moe Syzylak
Exams: 28.6 11.5 38.3 41.7 



## Future Improvements
Support for adding/removing exams dynamically

Weighted grading system

File‑based student import/export

GUI or web interface

Sorting students by grade or name
