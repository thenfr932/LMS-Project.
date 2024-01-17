# Learning Management System (LMS) with Tkinter and SQLite

A simple Learning Management System implemented using Tkinter for the graphical user interface and SQLite for the database. This LMS allows users to log in, enroll in courses, track their progress, and view their marks.

## Features

- **User Authentication:**
  - Regular users and teachers can log in with their credentials.
  - Separate panels for regular users and teachers.

- **Course Management:**
  - View available courses.
  - Enroll in courses.

- **Progress Tracking:**
  - Track course progress for enrolled users.
  - Mark courses as completed.

- **Teacher Features:**
  - Teachers can add marks for students.
  - Teachers can create announcements.
  - Teachers can add new courses.

## Database Structure

The SQLite database includes tables for users, courses, progress, teachers, marks, and announcements.

## Graphical User Interface (GUI)

The Tkinter library is used to create an intuitive GUI with frames for login, sign-up, the main menu, the teacher interface, and a marks display frame.

## Usage

1. Clone the repository:

    ```bash
    git clone https://github.com/thenfr932/learning-management-system.git
    cd learning-management-system
    ```

2. Install the required packages:
   ```bash
    pip install sqlite
    pip install tkinter
   ```
   
4. Run the application:

    ```bash
    python main.py
    ```

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request.

