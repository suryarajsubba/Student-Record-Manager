# Student Record Manager in C

A menu-driven Student Record Manager built using **C programming**, structures, functions, and file handling. It allows users to store student details in a file, display records, and calculate average marks.

## Features

- **Add Student:** Enter a student's name, age, and marks.
- **Display Students:** View all saved student records.
- **Calculate Average:** Calculate the average marks of all students.
- **Above-Average Students:** Display students whose marks are greater than the average.
- **File Handling:** Store student records in `students.txt` so they remain available after the program closes.
- **Menu-Driven Interface:** Navigate through the program using a simple menu.

## Concepts Used

- Structures (`struct`)
- Functions
- Arrays and strings
- Loops and conditional statements
- File handling (`fopen`, `fprintf`, `fscanf`, `fclose`)
- User input and output

## How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/suryarajsubba/Student-Record-Manager.git
```

### 2. Open the Project Folder

```bash
cd Student-Record-Manager
```

### 3. Compile the Program

If your C source file is named `main.c`, run:

```bash
gcc main.c -o student_manager
```

### 4. Run the Program

```bash
./student_manager
```

**Requirement:** GCC or another compatible C compiler.

## Data Storage

Student records are stored in a text file named `students.txt`. The program uses file handling to save new records and read existing ones.

**Note:** Avoid storing sensitive personal information in the records file.

## Learning Goals

This project helped me practice structures, functions, strings, and file handling in C while building a practical, menu-driven application.

## Author

**Surya Raj Subba**

- GitHub: [@suryarajsubba](https://github.com/suryarajsubba)
- Project Repository: [Student Record Manager](https://github.com/suryarajsubba/Student-Record-Manager)

---

*Built as part of my journey to improve my programming skills in C.*
