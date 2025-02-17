# Student Registration System

This is a Java-based **Student Registration System** that allows users to manage student records efficiently. The system provides functionalities such as registering students, deleting records, searching students, storing and loading data from files, and handling student grades based on module marks.

## Features
- ✅ Check available seats
- ✅ Register students with an ID
- ✅ Delete students from the system
- ✅ Find students by their ID
- ✅ Store student details into a file
- ✅ Load student details from a file
- ✅ View students sorted by name
- ✅ Add additional student details (name and module marks)

## Technologies Used
- Java (JDK 11+ recommended)
- File Handling (for data persistence)
- Object-Oriented Programming (OOP concepts)

## Project Structure
```
📂 Student-Registration-System
 ├── src
 │   ├── Main.java          # Entry point of the application
 │   ├── Student.java       # Student class to store student details
 │   ├── Module.java        # Module class to store module marks
 ├── output.txt            # Data file to store student records
 ├── README.md             # Project documentation
 └── .gitignore            # Git ignore file
```

## How to Run the Project
1. **Clone the Repository**
   ```sh
   git clone https://github.com/helithjay/Student-Activity-Management-System-Using-Classes-.git
   cd Student-Registration-System
   ```
2. **Compile the Java Files**
   ```sh
   javac src/*.java
   ```
3. **Run the Program**
   ```sh
   java src.Main
   ```

## Example Output
```
1. Check available seats
2. Register student (with ID)
3. Delete student
4. Find student (with student ID)
5. Store student details into a file
6. Load student details from the file to the system
7. View the list of students based on their names
8. Add additional details
Enter what you want to do (use number):
```

## Future Enhancements
- 🔹 Implement a GUI using JavaFX
- 🔹 Add a database connection instead of file storage
- 🔹 Improve search functionality with sorting and filtering

## Contributing
Feel free to fork this repository and submit pull requests. Contributions are welcome! 😊

## License
This project is licensed under the **MIT License**.
