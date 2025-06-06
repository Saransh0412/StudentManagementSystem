# Student Management System 📚

A simple Java-based console application that allows users to manage students, their personal details, and course enrollments.

## 🚀 Features

- Add new students
- Assign students to courses
- Display student details
- Display all enrolled courses
- Object-oriented design with class hierarchy:
  - `Person` → `Student`
  - `Course`
  - `StudentManagementSystem` (Main controller)

## 🧠 Project Structure

```

.
├── Course.java
├── Course.class
├── Person.java
├── Person.class
├── Student.java
├── Student.class
├── StudentManagementSystem.java
├── StudentManagementSystem.class

````

## 🛠️ Technologies Used

- Java 8 or above
- Object-Oriented Programming (OOP) principles
- CLI-based user interface

## 🧾 Class Overview

### ✅ `Person`
Base class containing personal information like name and age.

### ✅ `Student` (extends `Person`)
Represents a student with additional attributes like ID and list of enrolled `Course` objects.

### ✅ `Course`
Encapsulates course-related data including course code, title, and credits.

### ✅ `StudentManagementSystem`
Main class that contains the logic to interact with students and courses using a console-based menu.

## ▶️ How to Run

### 1. Compile the project

```bash
javac *.java
````

### 2. Run the program

```bash
java StudentManagementSystem
```

## 📝 Sample Menu (Console UI)

```
1. Add new student
2. Enroll student in course
3. Display student details
4. Display all students
5. Exit
```

## 📂 Usage

Follow the prompts in the terminal to manage students and their enrolled courses. The system stores all data in memory during the session.

## 🧑‍💻 Author

* **Saransh Bhargava**

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
