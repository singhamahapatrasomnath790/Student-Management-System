# Student Management System

A simple **Student Management System** built using **HTML, CSS, and JavaScript**. The application allows users to manage student records through a clean and interactive interface.

## 🚀 Tech Stack

* **HTML5** — Structure and layout
* **CSS3** — Styling and responsive design
* **JavaScript** — DOM manipulation and application logic

## ✨ Features

* **Add Students** — Create new student profiles with details such as name, age, grade, degree, and email.
* **View Students** — Display all student records in a structured table.
* **Edit Students** — Update the details of an existing student using the edit functionality.
* **Delete Students** — Remove student records from the list.
* **Search Students** — Search and filter students by:

  * Name
  * Email
  * Degree
* **Dynamic UI** — Student information is rendered and updated dynamically using JavaScript DOM manipulation.

## 📋 Student Information

Each student record contains the following properties:

| Property | Description                       |
| -------- | --------------------------------- |
| ID       | Unique identifier for the student |
| Name     | Student's name                    |
| Age      | Student's age                     |
| Grade    | Student's academic grade          |
| Degree   | Student's degree/program          |
| Email    | Student's email address           |

## 🛠️ Functionality

### Add Student

Users can enter the student's:

* Name
* Age
* Grade
* Degree
* Email

After clicking **Add Student**, the new student is added to the students array and displayed in the table.

### Edit Student

Each student has an **Edit** option. When selected:

1. The student's existing information is loaded into the form.
2. The **Add Student** button changes to **Edit Student**.
3. The user can modify the required information.
4. The updated information is reflected in the student list.

### Delete Student

Users can delete a student directly from the table using the **Delete** option.

### Search Student

The search functionality allows users to quickly find students based on their:

* Name
* Email
* Degree

## 📦 Sample Student Data

```javascript
const students = [
  {
    ID: 1,
    name: "Alice",
    age: 21,
    grade: "A",
    degree: "Btech",
    email: "alice@example.com"
  },
  {
    ID: 2,
    name: "Bob",
    age: 22,
    grade: "B",
    degree: "MBA",
    email: "bob@example.com"
  },
  {
    ID: 3,
    name: "Charlie",
    age: 20,
    grade: "C",
    degree: "Arts",
    email: "charlie@example.com"
  }
];
```

## 📁 Project Structure

```text
student-management-system/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

## 🎯 Implementation

The project is implemented using **vanilla JavaScript** and basic DOM manipulation techniques, including:

* `createElement()`
* `appendChild()`
* `removeChild()`
* `innerHTML`
* Event listeners
* Array manipulation

No external JavaScript libraries or APIs are required.

## 🎨 Design Reference

The UI is based on the provided Figma design:

[Figma Design](https://www.figma.com/file/I5kSEEoYpQtlSyNW9Z7YiD/F2)

## 💻 How to Run

1. Clone or download the repository.
2. Open the project folder.
3. Open `index.html` in a web browser.
4. Start managing student records.

## 📌 Project Purpose

This project demonstrates fundamental **frontend development and JavaScript DOM manipulation concepts**, including CRUD operations, form handling, dynamic rendering, and client-side search functionality.
