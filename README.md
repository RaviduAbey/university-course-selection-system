# University Course Selection System

This repository contains a Python program designed to help universities manage and recommend courses for students based on their enrollment history, gender, and semester. The program simplifies the process by evaluating a student's completed units and suggesting available courses for the upcoming semester.

## Overview
The **University Course Selection System** takes a structured approach to student enrollment, providing recommendations for the next semester based on the following criteria:
- Completed units
- Gender
- Semester status (new or returning)

By streamlining course recommendations, this program aims to reduce administrative work and provide an efficient way for students to explore their course options.

## Features
- **Student Data Management**: Input student records, including name, ID, gender, completed units, and semester.
- **Course Recommendations**: Based on the student's gender and passed units, the program suggests the courses they are eligible for.
- **Custom Messages**: Provides specialized messages for female students and new students, enhancing the personalization of the enrollment process.

## Input Structure
- **Course Structure**: A list of dictionaries that holds details like unit codes, names, prerequisites, and the semester in which courses are offered.
- **Student Records**: A list of dictionaries containing each student's name, gender, student ID, number of units passed, and semester status.

## Program Logic
1. The program iterates through the list of students, displaying each student's details.
2. It checks the courses that each student is eligible to enroll in based on their previously passed units and gender.
3. For new students or female students who have completed the female-only unit, the program provides additional recommendations.
4. Outputs include a personalized course recommendation for each student.

## How It Works
- **Loops and Conditions**: The program uses loops to iterate through students and if-else conditions to filter course recommendations based on gender and passed units.
- **Testing and Output**: The program handles various scenarios, such as students with no passed units, students who have passed specific units, and gender-based course eligibility.

## Example Output
- Displays student details: Name, ID, gender, units passed, and semester.
- Shows course recommendations based on the student's records.
- Custom messages for female students and new students.

## Future Enhancements
- Add support for more complex prerequisite validation.
- Implement a graphical user interface (GUI) to enhance user experience.
- Allow for customization of course structures for different universities.

## License
This project is licensed under the MIT License.

