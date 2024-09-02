# Quiz Management System

# Quiz Management System
## Introduction

The **Quiz Management System** is designed to streamline the process of quiz creation and evaluation. It is a console-based application that allows for different user roles, including administrators and students, to interact with quizzes in a controlled environment.
The Quiz Management System employs various object-oriented programming (OOP) concepts to enhance modularity, reusability, and maintainability:

- **Class**: The system defines multiple classes, such as `User`, `Student`, `Staff`, `Quiz`, and `QuizResultHandler`, which serve as blueprints for creating objects with specific properties and behaviors.
  
- **Encapsulation**: Data members are encapsulated within classes using access specifiers (`private`, `protected`, `public`), protecting them from unauthorized access and misuse. For example, the `Quiz` class encapsulates quiz details, and only specific methods can modify or access these details.

- **Inheritance**: The system uses inheritance to promote code reuse. For instance, `Student` and `Staff` classes inherit from the `User` class, sharing common attributes and behaviors while also having specific features.

- **Abstraction**: By exposing only essential details and functionalities, the system simplifies complex real-world entities into manageable code. Classes like `Quiz` provide only the necessary interfaces for quiz functionality, hiding internal implementation details.

- **Polymorphism**: Polymorphic behavior allows objects to be treated as instances of their parent class, enhancing flexibility. Methods in the base `User` class can be overridden in derived classes like `Student` and `Staff` to provide specialized behavior.

- **Composition**: The system demonstrates composition by using objects of one class within another class to achieve complex functionality. For instance, `QuizResultHandler` manages results using instances of `Quiz` and `Student`.

## Project Scope

This system aims to:

- Provide an easy-to-use platform for creating, managing, and taking quizzes.
- Allow real-time feedback and automatic result card generation for students.
- Support user authentication and role-based access control.

## Features

- **User Authentication and Authorization**: Secure login and registration for both students and administrators.
- **Quiz Creation and Management**: Admins can create, edit, and delete quizzes.
- **Randomization of Quiz Questions**: Quizzes are generated with random questions to ensure variety.
- **Immediate Feedback**: Students receive instant feedback after quiz completion.
- **High-Score Tracking**: The system maintains a hall of fame to display high scores.
- **Result Card Generation**: Automatic result cards are generated for students post-quiz.

## User Roles

### Admin
- Manage subjects and quizzes.
- Set quiz rules and manage student reports.
- View high scores and student results.

### Student
- Take quizzes and view results.
- Access the hall of fame to see high scores.
- Send reports to admin if issues are encountered.

## System Requirements

- **Operating System**: Windows
- **Programming Language**: C++
- **Database**: Simple text files (.txt)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/username/quiz-management-system.git
    ```
2. Navigate to the project directory:
    ```bash
    cd quiz-management-system
    ```
3. Compile the C++ source files using your preferred compiler:
    ```bash
    g++ -o QuizSystem main.cpp
    ```
4. Run the executable:
    ```bash
    ./QuizSystem
    ```

## Usage

### Admin Portal

- **Login/Registration**: Admins can log in using valid credentials or register if not already registered.
- **Subject Management**: Admins can add, update, delete, view, and search subjects.
- **Quiz Management**: Admins can manage quizzes, including adding, updating, and deleting quizzes based on subject difficulty.
- **Manage Quiz Rules**: Set rules for quizzes such as passing marks, total questions, and scoring rules.
- **View and Manage Reports**: Admins can view and approve student-submitted reports regarding issues.

### Student Portal

- **Login/Registration**: Students can log in or register if not already registered.
- **Take Quiz**: Students can start a quiz, view rules, and receive immediate feedback.
- **View Hall of Fame**: Students can check high scores and their rankings.
- **Send Report**: Students can report any issues they encounter to the admin.

![quiz management](https://git![subject management ](https://github.com/user![quiz management](https://github.com/user-attachments/assets/0454b09f-853d-4c50-9c19-e9f0df36c22c)
-attachments/assets/ff7742ae-4001-4f51-8170-1fc99cd7fb44)
hub.com/user-attachments/assets/2c30077f-be22-4121-af68-5a7e1cb36f74)

![admin menu](https://github.com/user-attachments/assets/2b5be91a-9dc5-455b-8d61-c1ba522954e1)

