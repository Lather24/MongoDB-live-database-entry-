# Student Admission Management System Using MongoDB & Python

This project demonstrates a **live database entry system** where student admission details are managed using **MongoDB** (local and Atlas) with a Python interface. The program allows real-time database updates through menu-based user input.

## Features
1. **Student Admission**: Add student details to the MongoDB database.  
2. **Search by Name**: Retrieve student details based on their name.  
3. **Search by ID**: Fetch student information using unique student IDs.  
4. **Update Records**: Modify existing student details in the database.  
5. **Delete Records**: Remove a student entry from the database.  
6. **Display All Records**: View all stored student records.  
7. **Exit**: Terminate the program.

---

## Workflow
1. The program starts with a menu-driven interface.
2. User presses a key (e.g., `1` for admission, `2` for search, etc.).
3. Based on the input, the respective operation is performed on the live database.
4. MongoDB is updated in real-time (locally or via Atlas).

---

## Python Libraries Used
- **pymongo**: To interact with the MongoDB database.  
- **datetime**: For timestamp management.  
- **sys**: To handle program termination.

---

## MongoDB Setup
1. Install MongoDB locally or set up an Atlas cluster.
2. Create a database named `student_management`.
3. Create a collection named `students`.

## Conclusion
This README is concise and formatted for a one-page overview, covering the project details, features, setup, and code functionality.
