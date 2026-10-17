# Student Management System (Java)

A console-based Java application for managing student records. It is designed for beginners and runs in Eclipse IDE using only the Java standard library.

## Features

- Add a student
- View all student records
- Search by student ID
- Update a student's details
- Delete a student record with confirmation
- Calculate total students, average GPA, highest GPA, and lowest GPA
- Save records to a local text file and load them on the next run
- Input validation for numbers, semester, and GPA

## Technologies and concepts

- Java
- Object-oriented programming (classes, objects, encapsulation)
- `ArrayList`
- File handling with `java.nio.file`
- Exception handling
- Loops, methods, conditionals, and input validation

## Requirements

- JDK 8 or later
- Eclipse IDE for Java Developers

## Run in Eclipse

1. Extract the ZIP file.
2. Open Eclipse.
3. Select **File → New → Java Project**.
4. Name the project `StudentManagementSystem`.
5. If Eclipse creates a `module-info.java` file, you can delete it for this beginner project.
6. Copy the three `.java` files from the extracted `src` folder into the Eclipse project's `src` folder.
7. Make sure the files are in the default package (do not add a `package` declaration).
8. Right-click `Main.java` → **Run As → Java Application**.

The app creates `data/students.txt` relative to the working directory when records are saved.

## Upload to GitHub

1. Create a new empty repository on GitHub named `StudentManagementSystem`.
2. Do not add a README on GitHub if you plan to push this folder's README.
3. Open a terminal in the extracted project folder.
4. Run:

```bash
git init
git add .
git commit -m "Initial commit: Student Management System"
git branch -M main
git remote add origin https://github.com/AjwadRehman/StudentManagementSystem.git
git push -u origin main
```

Replace `YOUR-USERNAME` with your GitHub username.

If Git asks you to sign in, complete GitHub's authentication prompt. Do not put passwords or API tokens in your source code.

## Example test

Try adding:
- ID: `101`
- Name: `Ayesha Khan`
- Department: `Software Engineering`
- Semester: `3`
- GPA: `3.72`

Then view the records, search for ID `101`, update the record, and restart the application to verify that the record persists.

## Project structure

```text
StudentManagementSystem/
├── src/
│   ├── Main.java
│   ├── Student.java
│   └── StudentManager.java
├── data/
│   └── students.txt
├── .gitignore
└── README.md
```
