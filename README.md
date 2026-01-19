Java Swing Form Validator
=========================

Overview
--------
This project is a desktop-based User Registration Form developed using Java Swing.
The application validates user input and provides clear visual feedback based on
validation results. It demonstrates core Java concepts including event-driven
programming, regular expressions, and modular code design.

Features
--------
- Java Swing-based graphical user interface
- Input fields for Name, Age, and Email
- Input validation logic:
  - Name must be non-empty and contain only alphabetic characters
  - Age must be a numeric value between 1 and 120
  - Email must follow a valid format (regex-based validation)
- Dynamic status messages for success and error cases
- Color-based visual feedback for validation results
- Confirmation dialogs using JOptionPane
- Reset and clear functionality with user confirmation

Technologies Used
-----------------
- Java
- Java Swing
- Regular Expressions
- Event Handling (ActionListener)
- Object-Oriented Programming principles

Project Structure
-----------------
src/
└── linearSearch/
    └── FormValidator.java

Execution Instructions
----------------------
1. Clone the repository:
   git clone https://github.com/your-username/java-form-validator.git

2. Navigate to the project directory:
   cd java-form-validator

3. Compile and run the application:
   javac FormValidator.java
   java FormValidator

Learning Outcomes
-----------------
- Developed a desktop GUI using Java Swing
- Implemented robust input validation with regex and exception handling
- Applied event-driven programming concepts
- Improved code readability through modular methods
- Enhanced user experience with real-time feedback and dialogs

Future Improvements
-------------------
- Replace absolute positioning with layout managers
- Introduce MVC architecture for better scalability
- Add persistent storage using a database
- Enhance UI styling or migrate to JavaFX

Author
------
Kaushiki
Student Engineer
