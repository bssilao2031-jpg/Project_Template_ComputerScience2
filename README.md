# 📌 Project Proposal

## 📝 Project Title

**Student Grade Tracker: An Academic Performance Monitoring and Analysis System**

---

## 🔍 Problem Statement

Students need an organized and convenient way to manage, monitor, and analyze their academic performance. However, keeping track of grades across different subjects and grading periods can become difficult when records are scattered or manually organized.

The Student Grade Tracker aims to address this problem by providing a system that allows users to manage academic grade records, calculate grade statistics, and generate academic performance reports.

The project is relevant to the student dataset because it uses student information and academic grades to organize and analyze academic performance.

---

## 🎯 Project Objectives

- To develop a program that allows users to add, view, update, and delete student grade records.
- To implement JSON file handling for saving and loading grade records as persistent data.
- To calculate grade statistics, including average, highest, and lowest grades, and generate academic performance reports.

---

## ⚙️ Planned Features

1. **Add Grade Records** – Allows users to enter student information and academic grades.
2. **View Grade Records** – Displays previously saved student grade records.
3. **Update Grade Records** – Allows users to modify existing grade information.
4. **Delete Grade Records** – Allows users to remove selected grade records.
5. **Grade Statistics** – Calculates the average, highest, and lowest grades.
6. **Academic Performance Report** – Generates a summary of academic performance.
7. **Persistent Data Storage** – Saves and loads grade records using JSON files.

---

## ⌨️ Planned Inputs and Outputs

### Inputs

- Student ID
- Student Name
- Subject
- Quarter
- Grade
- User's selected menu option

### Outputs

- Displayed student grade records
- Successfully added, updated, or deleted record messages
- Calculated average grade
- Highest grade
- Lowest grade
- Academic performance report
- Invalid selection message
- Exit confirmation message

---

## 🧠 Logic Plan

The program follows a menu-driven structure. It begins by loading previously saved grade records from a JSON file and displaying the main menu. The user selects an operation, and the program performs the corresponding task. After completing an operation, the program returns to the main menu. This process repeats until the user selects the Exit option, which saves the records before ending the program.

### Pseudocode

```text
START

Load saved grade records from JSON file

REPEAT
    Display main menu:
        1. Add Grade Record
        2. View Grade Records
        3. Update Grade Record
        4. Delete Grade Record
        5. Calculate Grade Statistics
        6. Generate Performance Report
        7. Exit

    Ask user to select an option

    IF option = 1 THEN
        Enter and validate grade information
        Add new grade record
        Save records to JSON file

    ELSE IF option = 2 THEN
        Display all saved grade records

    ELSE IF option = 3 THEN
        Select and update grade record
        Save updated records to JSON file

    ELSE IF option = 4 THEN
        Select and delete grade record
        Save updated records to JSON file

    ELSE IF option = 5 THEN
        Calculate average, highest, and lowest grades
        Display calculated results

    ELSE IF option = 6 THEN
        Generate academic performance report
        Display performance report

    ELSE IF option = 7 THEN
        Save records to JSON file
        Display exit message

    ELSE
        Display invalid selection message

UNTIL user chooses Exit

END
```

### Flowchart

The program flowchart was designed using **Flowgorithm**. It illustrates the program's main menu, user input, decision-making process, available operations, and exit procedure.

**Flowchart Image:** Insert the exported Flowgorithm flowchart image here.

---

## 📂 GitHub Repository Link

https://github.com/bssilao2031-jpg/Project_Template_ComputerScience2

---

## 👥 Project Team

- Brent Silao
- Martine Plaza
- Andres Real
