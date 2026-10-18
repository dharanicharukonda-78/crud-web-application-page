

# Web Application – Student Management System

## Project Overview

This is a web-based Student Management System developed using Python, Flask, HTML, CSS, and SQLite.

The application allows users to manage student details through a web interface. Users can add new students, view student records, update existing details, and delete records.

## Features

- Add student details
- View all student records
- Update student information
- Delete student records
- Store student information in an SQLite database
- Simple and user-friendly web interface

## Technologies Used

- **Frontend:** HTML, CSS
- **Backend:** Python, Flask
- **Database:** SQLite
- **Tools:** Visual Studio Code, Git, GitHub

## Project Structure

```text
crud-web-application-page/
├── app.py
├── README.md
├── .gitignore
└── templates/
    └── index.html
```

The `students.db` database file is created automatically when the application starts. It is excluded from GitHub using `.gitignore`.

## Application Workflow

1. The user opens the web application in a browser.
2. The HTML form collects student name, email, and course.
3. Flask handles the user's requests.
4. SQLite stores and manages student records.
5. The updated student records are displayed on the web page.

## CRUD Operations

| Operation | Description |
|---|---|
| Create | Add a new student |
| Read | View student records |
| Update | Edit existing student details |
| Delete | Remove a student record |

## Requirements

- Python 3 installed
- pip package manager
- Flask

## How to Download and Run

### 1. Clone the repository

```bash
git clone https://github.com/dharanicharukonda-78/crud-web-application-page.git
```

### 2. Open the project folder

```bash
cd crud-web-application-page
```

### 3. Install Flask

```bash
python -m pip install flask
```

### 4. Run the application

```bash
python app.py
```

### 5. Open the application

Open this URL in your browser:

http://127.0.0.1:5000

The application will create the SQLite database and the students table automatically when it starts.

## Learning Outcome

This project demonstrates the connection between a web frontend, a Python Flask backend, and an SQLite database, including the four CRUD operations.

## Author

Dharani Charukonda

