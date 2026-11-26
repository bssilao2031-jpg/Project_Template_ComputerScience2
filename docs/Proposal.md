# Student Grade Tracker: A Program for Managing and Checking Student Grades

**Project Milestone 1: Project Proposal**

**Group Members:**
- Brent Silao
- Martine Plaza
- Andres Real

## 1. Project Title

**Student Grade Tracker: An Academic Performance Monitoring and Analysis System**

## 2. Brief Description

The Student Grade Tracker is a data management application designed to help students record, organize, and monitor their academic grades. The application allows users to add, view, update, and delete grade records. It can also calculate grade averages, identify the highest and lowest grades, and generate academic performance summaries. The system will use JSON files to store information so that previously saved records can still be accessed when the application is reopened.

## 3. Problem Statement

### Problem Identified

Students may find it difficult to organize their academic grades and monitor their performance across different subjects and grading periods. Manually recording grades and calculating averages can be time-consuming and may lead to errors. Without an organized system, keeping track of academic progress can become challenging. The Student Grade Tracker aims to provide a convenient way to manage grade records and analyze academic performance.

### Target Users / Beneficiaries

- Students who want to organize and monitor their academic grades.
- Learners who want to calculate and compare their grades across subjects.
- Students who want to keep track of their academic performance and progress.

### Project Objectives

The project aims to achieve the following objectives:

1. To develop an application that allows users to add, view, update, and delete academic grade records.
2. To implement JSON-based persistent data storage to save and retrieve student grade information.
3. To calculate and present academic statistics, including average, highest, and lowest grades, to help students monitor their academic performance.

## 4. Outline of Features

| Feature | Description | Persistent Data Used |
|---|---|---|
| Feature 1: Add and Manage Grade Records | Allows users to add new grade records and update or delete existing information. | Student ID, student name, subject, quarter, and grade |
| Feature 2: View Grade Records | Displays all saved student grade records, including student information, subjects, quarters, and grades. | Saved student grade records |
| Feature 3: Grade Calculator | Calculates the average grade and identifies the highest and lowest recorded grades. | Stored grades and subject information |
| Feature 4: Academic Performance Report | Generates summaries and comparisons of grades across different subjects and grading periods. | Student records, subjects, quarters, and grades |
| Feature 5: Save and Load Records | Saves grade records in a JSON file and retrieves previously saved records when the application is reopened. | Student grade records stored in the JSON file |

## 5. Description of Data to Be Collected and Stored as Persistent Data

| Data Field | Description | Purpose/Use |
|---|---|---|
| Student ID | A unique identification number assigned to the student. | Used to identify whose grades are being recorded. |
| Student Name | The full name of the student. | Used to identify the student associated with each grade record. |
| Subject | The academic subject associated with the grade. | Used to organize and compare grades by subject. |
| Quarter | The grading period when the grade was recorded. | Used to organize and compare academic performance across quarters. |
| Grade | The numerical grade received by the student. | Used to calculate averages and generate performance summaries. |

*Note: The identified data fields may still be revised and finalized during the Third Quarter.*

## 6. Logic Plan

### Pseudocode

```text
START

Load saved grade records from JSON file.

REPEAT
    Display the main menu:

    1. Add Grade Record
    2. View Grade Records
    3. Update Grade Record
    4. Delete Grade Record
    5. Calculate Grade Statistics
    6. Generate Performance Report
    7. Exit

    Ask the user to select an option.

    IF option is 1:
        Enter and validate grade information.
        Add the new record.
        Save records.

    ELSE IF option is 2:
        Display all saved records.

    ELSE IF option is 3:
        Select and update a grade record.
        Save updated records.

    ELSE IF option is 4:
        Select and delete a grade record.
        Save updated records.

    ELSE IF option is 5:
        Calculate average, highest, and lowest grades.
        Display the results.

    ELSE IF option is 6:
        Generate an academic performance report.
        Display the report.

    ELSE IF option is 7:
        Save records.
        Display exit message.

    ELSE:
        Display an invalid selection message.

UNTIL the user chooses Exit.

END
```

## 7. Sample Wireframe of the Application

### Flowchart

The application flowchart illustrates the following process:

1. Start the application.
2. Load saved JSON records.
3. Display the main menu.
4. Allow the user to choose an operation.
5. Perform the selected operation.
6. Save changes when necessary.
7. Return to the main menu or exit.

**Flowchart Image:** Insert the exported flowchart image here.
<img width="959" height="520" alt="image" src="https://github.com/user-attachments/assets/4cb11a26-ddb6-4bd0-9bc5-71bb9c8251d8" /> 

### Screen Descriptions

- **Screen 1 – Main Dashboard:** Displays the main menu, overall grade average, grade overview, recent grades, and quick-access buttons.
- **Screen 2 – Grade Management:** Allows users to add, view, update, and delete student grade records.
- **Screen 3 – Performance Report:** Displays calculated averages, highest and lowest grades, and comparisons across subjects and grading periods.

## 8. Task Schedule and Assigned Team Members

| Task/Activity | Assigned Member(s) | Target Date | Status |
|---|---|---|---|
| Project planning | Brent Silao, Martine Plaza, Andres Real | To be determined | In Progress |
| Feature development | All members | To be determined | Pending |
| Data design | Brent Silao and Martine Plaza | To be determined | Pending |
| Wireframe creation | Andres Real | To be determined | In Progress |
| Documentation | Brent Silao and Martine Plaza | To be determined | In Progress |
| Proposal review and finalization | All members | To be determined | Pending |
| GitHub repository organization and submission | All members | To be determined | Pending |

## 9. Additional Notes / Considerations

The proposed application will be developed using Python and will apply the programming concepts discussed in Computer Science 2, including functions and arguments, iterative control structures, arrays, and programming libraries.

The system will use JSON files or similar persistent data structures to store and retrieve academic records. It will support Create, Read, Update, and Delete (CRUD) operations. Input validation and testing will also be considered to ensure that the application handles information correctly and produces accurate results.

The proposed features and data fields may still be revised and improved as the project progresses through the succeeding milestones.

## GitHub Repository

https://github.com/bssilao2031-jpg/Project_Template_ComputerScience2

