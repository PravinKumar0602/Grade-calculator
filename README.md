# Student Grade Calculator 🎓

A robust, console-based Java application designed to automate academic performance evaluation.

## 📖 Project Description

The **Student Grade Calculator** is a functional, console-based application developed using the **Java** programming language. Its primary purpose is to automate the process of calculating a student's total marks, determining their average percentage, and assigning an appropriate letter grade based on their academic performance. This project serves as a practical demonstration of core programming fundamentals and their application in solving real-world data-processing tasks.

### Technical Implementation
The project is built around the principles of **Object-Oriented Programming (OOP)** and efficient control flow. Key technical features include:
*   **Dynamic Data Handling:** Utilizing the `Scanner` class to capture real-time user input, allowing the program to be interactive and adaptable to different student profiles.
*   **Array Management:** Using **Arrays** to store marks for an arbitrary number of subjects. This demonstrates an understanding of data structures and how to iterate through them using `for` loops.
*   **Decision-Making Logic:** Implementing a robust `if-else` ladder to categorize percentages into specific grades (ranging from A+ to Fail), ensuring accurate performance evaluation.
*   **Modular Code Structure:** The calculation logic is separated into distinct methods. This modularity ensures the code is readable, maintainable, and easy to debug—a crucial practice in professional software development.

### Project Goals and Utility
The goal of this project was to move beyond theoretical syntax and build a tool that manages data flow from input to output. It addresses a common administrative need: converting raw scores into meaningful summaries. By automating the math, the program eliminates human error and provides an instant performance report.

### Future Scope
While currently a terminal-based tool, this project is designed with scalability in mind. The logic can easily be integrated into a **Graphical User Interface (GUI)** using Java Swing or JavaFX. Additionally, it could be expanded to include file handling, allowing users to save student records permanently into a `.txt` or `.csv` file.

This project highlights a strong grasp of Java basics, logical thinking, and the ability to transform a simple concept into a structured, functional software solution.

---

## 🛠️ Requirements
* **Java JDK** (8 or higher)
* Terminal or any Java-supported IDE

## 🚀 How to Run
1. **Compile the program:**
   ```bash
   javac GradeCalculator.java
Run the application:

Bash
java GradeCalculator


## 📊 Grading Scale
| Percentage | Grade |
|------------|-------|
| 90% - 100% | A+    |
| 80% - 89%  | A     |
| 70% - 79%  | B     |
| 60% - 69%  | C     |
| 50% - 59%  | D     |
| Below 50%  | Fail  |

---
