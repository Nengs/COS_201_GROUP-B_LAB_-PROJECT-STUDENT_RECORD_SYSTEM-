# Project README.md File
This is C program developed as a COS 201 Group B lab project for storing, processing, and retrieving student data. The system allows efficient management of student records, including registration, academic performance tracking, and data retrieval, demonstrating practical use of file handling and structured programming in C.

# COS_201 Student Record System (Group B Lab Project)

A **C program** for **storing, processing, and retrieving student data**, developed as a COS 201 Group B lab project. This system demonstrates practical use of **structured programming, dynamic memory management, and file handling** in C.  

----- Features-----

- **Insert, delete, and update student records** with validation.
- **View all students** in a formatted table with pass/fail status.
- **Search for students by ID** and view detailed information.
- **Compute average scores** of all students.
- **Sort students by score** in ascending or descending order.
- **Save and load records from CSV files** for persistent storage.
- **Interactive menu with color-coded console output** for better user experience.

--- Student Record Structure ---

Each student record includes:

- **Name**  
- **ID**  
- **Score**  
- **Status** (Passed if score > 40, else Failed)  
- **Last Modified Date**

--- Getting Started ---

1. *Compile the program:**  
   ```bash
   gcc -o student_db student_record_system.c
2. Run the program:
```bash
./student_db


