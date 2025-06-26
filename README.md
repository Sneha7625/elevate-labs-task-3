# 📚 Library Management System (CLI - Java)

## 📌 Task Overview

**Task 3:** Create a CLI-based Library Management System using Object-Oriented Programming in Java.

---

## 🎯 Objective

Build a command-line interface application that allows users to:
- Add new books to the library
- View all available books
- Issue books (mark them as borrowed)
- Return books (make them available again)

---

## 🛠 Tools Used

- Java (JDK)
- VS Code / IntelliJ
- Terminal / Command Prompt

---

## 🗂 Folder Structure

LibraryManagementSystem/
|_____src/
      |____ Book.java
      │____ Library.java
      |_____ User.java
      │_____ Main.java
|_____ README.md


---

## ✅ What I Did

1. Created a main project folder named `LibraryManagementSystem`.
2. Added a `src` directory to organize source files.
3. Created the following Java files:
   - `Book.java`: A class with attributes `title`, `author`, and `isIssued`. Includes methods to issue/return the book and display its status.
   - `Library.java`: Manages a list of books using `ArrayList<Book>`, with methods to add, view, issue, and return books.
   - `User.java`: A simple user class (for potential future expansion).
   - `Main.java`: Contains the main method and displays a menu for interacting with the library system.
4. Compiled and ran all Java files using terminal.
5. Tested all functionalities: add, issue, return, and view.

---

## 💡 Hints Followed

1. Used OOP concepts: created reusable and encapsulated classes.
2. Applied `ArrayList` to store and manage books.
3. Designed a loop-based CLI for continuous user interaction.
4. Kept logic modular by separating responsibilities across classes.

---

## 💬 Sample Menu

===== Library Menu =====

1.Add Book
2.Show Books
3.Issue Book
4.Return Book
5.Exit
Choose an option:


---

## 📈 Outcome

- Learned and applied Object-Oriented Programming concepts in Java.
- Gained experience with:
  - Class design and interaction
  - Java collections (`ArrayList`)
  - Encapsulation with methods and fields
  - Menu-driven console apps using loops and conditionals

---

## 📌 Deliverable

- Java program structured into multiple classes
- Functional CLI to manage a library's book inventory
- Source files: `Book.java`, `Library.java`, `User.java`, `Main.java`

