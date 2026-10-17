# 🎓 Student Grade Management System in Java

A robust, console-based student grade management application developed in Java as part of the **Java Programming Virtual Internship** at **CodeOrbit Tech** (Batch IND1).

---

## 📌 Project Overview
The **Student Grade Management System** is designed to streamline academic record-keeping. It allows educators and administrators to add student records, enter subject marks, compute overall percentages, automatically assign letter grades, and review student performance reports via an interactive command-line interface.

---

## ✨ Key Features
- **Student Record Management:** Add and manage student details (Name, Roll Number).
- **Marks & Score Tracking:** Record marks across multiple subjects with input range validation ($0-100$).
- **Automated Grade Calculation:** Computes total marks, average percentage, and evaluates corresponding letter grades ($A+, A, B, C, \text{or } F$).
- **Performance Summary Display:** Formatted console report cards detailing student performance.
- **Robust Exception Handling:** Catches non-numeric inputs using `InputMismatchException` and prevents invalid score ranges.
- **Continuous Operations:** Interactive loop allowing users to manage multiple students in one session.

---

## 🛠️ Technologies Used
- **Programming Language:** Java (JDK 8 or higher)
- **Core Concepts:** Object-Oriented Programming (OOP), Collections / Arrays, Exception Handling
- **Key Classes:** `java.util.Scanner`, `java.util.ArrayList`, `java.util.InputMismatchException`
- **IDE:** Eclipse / IntelliJ IDEA / VS Code
- **Version Control:** Git & GitHub

---

## ⚙️ How to Setup & Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/rathodravi5598/CODE_ORBIT_Student-GradeManagement-System.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd CODE_ORBIT_Student-GradeManagement-System
   ```

3. **Compile the Java source files:**
   ```bash
   javac *.java
   ```

4. **Run the program:**
   ```bash
   java Main
   ```
   *(Note: If your main class file has a different name such as `StudentGradeSystem`, replace `Main` accordingly)*

---

## 🖥️ Sample Console Output

```text
===================================================
     STUDENT GRADE MANAGEMENT SYSTEM
===================================================
Enter Student Name: Rathod Ravi
Enter Roll Number: 101
Enter Number of Subjects: 3

Enter Marks for Subject 1 (out of 100): 88
Enter Marks for Subject 2 (out of 100): 92
Enter Marks for Subject 3 (out of 100): 85
---------------------------------------------------
               STUDENT REPORT CARD                 
---------------------------------------------------
Roll No      : 101
Student Name : Rathod Ravi
Total Marks  : 265 / 300
Percentage   : 88.33%
Grade        : A
Status       : PASSED
===================================================
Do you want to process another student? (yes/no): no
Thank you for using the Grade Management System!
```

---

## 👨‍💻 Intern Details
- **Intern Name:** Rathod Ravi
- **Intern ID:** COT/IND1/56814
- **Role:** Java Programming Intern
- **Organization:** CodeOrbit Tech
- **Repository Link:** [CODE_ORBIT_Student-GradeManagement-System](https://github.com/rathodravi5598/CODE_ORBIT_Student-GradeManagement-System)
