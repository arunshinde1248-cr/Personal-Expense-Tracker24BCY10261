 Personal Expense Tracker (Java)
 Project Overview

The Personal Expense Tracker is a console-based Java application designed to help users efficiently manage and monitor their daily expenses. It allows users to record financial transactions, categorize spending, and analyze their expenses over time.

This project is developed as part of the BYOP (Bring Your Own Project) for the Programming in Java course. It demonstrates the practical application of core Java concepts to solve a real-world problem.

 Objectives
To provide a simple and effective way to track daily expenses
To help users analyze their spending habits
To implement Object-Oriented Programming concepts in Java
To use file handling for persistent data storage
To create a user-friendly CLI-based application

 Features
 Core Features
Add new expenses (amount, category, date, description)
View all recorded expenses
Calculate total spending
Generate monthly summaries

 Advanced Features
Category-wise expense report
Budget limit setting
Budget warning system
Persistent storage using file handling

 Technologies Used
Java (Core Java)
OOP Concepts (Encapsulation, Classes, Objects)
Collections Framework (ArrayList, HashMap)
File Handling (BufferedReader, FileWriter)
Scanner (User Input Handling)

 Project Structure
Personal-Expense-Tracker/
│── Expense.java
│── ExpenseManager.java
│── Main.java
│── expenses.txt
│── README.md

 How to Run the Project
🔹 Step 1: Compile the code
       javac *.java
🔹 Step 2: Run the application
      java Main

 Application Menu
===== PERSONAL EXPENSE TRACKER =====
1. Add Expense
2. View Expenses
3. Total Spending
4. Monthly Summary
5. Category Report
6. Set Budget
7. Check Budget
8. Exit

 

 Adding Expense
Enter amount: 200
Enter category: Food
Enter date (MM-YYYY): 03-2026
Enter description: Lunch

Expense added successfully!

 Viewing Expenses
200 | Food | 03-2026 | Lunch
500 | Travel | 03-2026 | Bus ticket

 Total Spending
Total Spending: 700

 Monthly Summary
Food: 200
Travel: 500
Total: 700

 Budget Warning
WARNING: Budget exceeded!

 Data Storage
All expenses are stored in a file named expenses.txt
Data is saved automatically when the program exits
Previously saved data is loaded when the program starts

 Error Handling
Handles invalid menu choices
Prevents crashes due to incorrect input
Displays user-friendly error messages

 Concepts Covered
Object-Oriented Programming (OOP)
Data Structures (ArrayList, HashMap)
File Handling (Read/Write operations)
Exception Handling
Menu-driven programming

 Challenges Faced
Managing file input/output operations
Handling user input efficiently
Designing modular and reusable code
Implementing category-wise analysis

 Future Enhancements
GUI version using JavaFX
Graphical charts (Pie/Bar charts)
Database integration (MySQL)
User authentication system
Export data to Excel/CSV

 Author
Arun Shinde.
B.Tech CSE,
VIT Bhopal University

 License

This project is developed for educational purposes only.

⭐ Final Note

This project demonstrates how basic programming concepts can be applied to solve real-life problems effectively. It is simple, efficient, and can be further extended into a full-scale application.
