# Functionality
This codebase serves as a backend system for managing student grades and courses. It allows users to perform CRUD operations on students, courses, and grades via HTTP endpoints. The system ensures data integrity by maintaining relationships between students, courses, and grades. Additionally, it provides functionalities like retrieving all grades, retrieving grades for a specific student or course, and updating grades.

## Entity Classes

### 1. Student
Represents a student with attributes such as id, name, birth date, and a list of grades.

### 2. Course
Represents a course with attributes such as id, subject, code, description, and a list of grades.

### 3. Grade
Represents the grade of a student in a course, with attributes like id, score, and references to both student and course.

## Controller Classes

### 1. StudentController
Handles HTTP requests related to student entities. It provides endpoints for retrieving, creating, and deleting students.

### 2. CourseController
Handles HTTP requests related to course entities. It provides endpoints for retrieving, creating, and deleting courses.

### 3. GradeController
Handles HTTP requests related to grade entities. It provides endpoints for retrieving, creating, updating, and deleting grades. It also provides endpoints for retrieving all grades, grades for a specific student, and grades for a specific course.

## Service Classes

### 1. StudentService
Contains business logic related to student entities, such as retrieving, creating, and deleting students.

### 2. CourseService
Contains business logic related to course entities, such as retrieving, creating, and deleting courses.

### 3. GradeService
Contains business logic related to grade entities, such as retrieving, creating, updating, and deleting grades.

## Repository Classes
The repository classes here typically interact with the database and handle CRUD (Create, Read, Update, Delete) operations for the respective entity types.
