#  Namitha1205 - Projects
#  Reverse Difference Number Series Analyzer(Java)

## Project Idea
This project is a Java-based application that analyzes a given number series and detects whether it follows a reverse difference pattern. If the pattern exists, it predicts the next number in the series.


## Formulas Used

- **Difference Formula**  
  dᵢ = aᵢ₊₁ − aᵢ  

- **Reverse Difference Pattern Condition**  
  dᵢ₊₁ − dᵢ = constant  

- **Next Value Formula**  
  nextDiff = d_last + constant  
  nextValue = a_last + nextDiff  


## Techniques Used

- Array Traversal  
- Pattern Recognition  
- Conditional Logic  
- Input Handling  
- Edge Case Handling  


## Features of the Project

### Core Features
- Detect reverse difference pattern  
- Calculate next number  
- Display intermediate steps (differences)  


## Technologies Used

- Java  
- Eclipse IDE  

---



# Library Management System (Java)

## Project Idea
This project is a Java-based Library Management System that allows users to manage books efficiently using a console-based interface. It supports adding, viewing, issuing, and returning books.

## Objective
To develop a simple system that demonstrates basic operations of a library using Java and object-oriented programming concepts.

## ⚙️ Features

### Core Features
- Add new books  
- View all books  
- Issue a book  
- Return a book  
- Menu-driven interface  

## Concepts Used

- Object-Oriented Programming (OOP)  
- Classes and Objects  
- ArrayList (Dynamic Storage)  
- Conditional Statements  
- Loops (do-while, for-each)  
- User Input Handling using Scanner  

## Data Structure Used

- **ArrayList**
  - Stores list of books dynamically  
  - Allows easy addition and traversal  

## Project Structure

- **Book Class**
  - Attributes: id, title, author, isIssued  
  - Represents each book  

- **LibraryManagement Class**
  - Handles all operations:
    - Add Book  
    - View Books  
    - Issue Book  
    - Return Book  

## Technologies Used

- Java  
- Eclipse IDE  

---


# ATM Management System (Java)

## Project Idea
This project is a Java-based ATM Management System that simulates basic banking operations such as checking balance, depositing money, and withdrawing money using a console-based interface.

## Objective
To implement a simple ATM system using Java that demonstrates real-world banking operations and core programming concepts.

## Features

### Core Features
- Check account balance  
- Deposit money  
- Withdraw money  
- Input validation for transactions  
- Menu-driven interface  

## Concepts Used

- Object-Oriented Programming (OOP)  
- Classes and Objects  
- Conditional Statements  
- Loops (do-while)  
- User Input Handling using Scanner  

## Project Structure

- **ATM Class**
  - Handles:
    - Balance checking  
    - Deposit operation  
    - Withdrawal operation  

- **ATM_management Class**
  - Contains main method  
  - Menu-driven system for user interaction  

## Technologies Used

- Java  
- Eclipse IDE  

---

# Student Management System (Java)

## Project Idea
This project is a Java-based Student Management System that allows users to manage student records efficiently using a console-based interface. It supports adding, viewing, searching, updating, deleting, and analyzing student data.

## Objective
To develop a system that manages student information and demonstrates core programming concepts like data handling, sorting, and searching.

---

## Features

### Core Features
- Add student details  
- Display all students  
- Search student by ID  
- Filter students based on marks  
- Calculate average marks  
- Sort students by marks (descending)  
- Update student details  
- Delete student records  
- Menu-driven interface  

## Concepts Used

- Object-Oriented Programming (OOP)  
- Classes and Objects  
- ArrayList (Dynamic Data Storage)  
- Lambda Expressions (for sorting & deletion)  
- Conditional Statements  
- Loops (do-while, for-each)  
- User Input Handling using Scanner  

## Data Structure Used

- **ArrayList**
  - Stores student records dynamically  
  - Allows easy insertion, deletion, and traversal  

## Project Structure

- **Student Class**
  - Attributes: studentId, name, age, course, marks  
  - Methods:
    - inputDetails()  
    - displayDetails()  

- **StudentManagementSystem Class**
  - Handles all operations:
    - Add  
    - Display  
    - Search  
    - Filter  
    - Average Calculation  
    - Sort  
    - Update  
    - Delete  

## Technologies Used

- Java  
- Eclipse IDE  

---


# ❌⭕ Tic Tac Toe Game (Java)

## Project Idea
This project is a Java-based Tic Tac Toe game that allows two players to play against each other in a console-based interface. The game checks for a winner after each move and declares the result accordingly.

## Objective
To develop a simple interactive game using Java that demonstrates logic building, condition checking, and user interaction.

## Features

### Core Features
- Two-player gameplay (X and O)  
- 3x3 game board  
- Input validation for row and column  
- Prevents overwriting filled cells  
- Automatic winner detection  
- Draw detection when board is full  
- Console-based interface  

## Concepts Used

- Arrays (2D Array for board)  
- Conditional Statements  
- Loops (for loop)  
- Functions/Methods  
- User Input Handling using Scanner  
- Game Logic Implementation  

## Game Logic

- Players take turns placing X or O  
- A player wins if:
  - All 3 rows match  
  - All 3 columns match  
  - Any diagonal matches  
- If all 9 moves are completed without a winner → Draw  

## Project Structure

- **Main Class: TicTacToe**
  - Handles:
    - Game loop  
    - Player turns  
    - Input handling  

- **Methods**
  - `initializeBoard()` → Initializes board with '-'  
  - `printBoard()` → Displays board  
  - `checkWinner()` → Checks winning condition  

## Technologies Used

- Java  
- Eclipse IDE  

---
