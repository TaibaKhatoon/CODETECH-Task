Name-Taiba Khatoon
Company-CODETECH IT SOLUTION
ID-CT08DS1874
Duration-10 JUNE TO 10 JULY
Mentor-SRAVANI GOUNI

Project Overview: Student Grades Management System
The Student Grades Management System is a Java console application designed to help users track and manage student grades. The application allows users to input grades for different subjects or assignments, calculate the average grade, and display the overall grade along with additional information such as letter grades and GPA. The system provides a simple and user-friendly interface to perform these tasks.

Features
Add Grade:

Users can add grades for different subjects or assignments.
Each grade entry includes a subject name and a numerical grade (0-100).
Calculate Average Grade:

The system calculates the average grade of all entered grades.
Displays the calculated average grade to the user.
Display Overall Grade Information:

Shows the average grade, corresponding letter grade, and GPA based on the entered grades.
Exit:

Allows users to exit the application gracefully.
Project Structure
Main Class (StudentGrades.java):

Entry point of the application.
Provides the main menu for interacting with the system.
Manages user input and directs the flow of the program.
Grade Class (Grade.java):

Represents individual grade entries.
Contains attributes for the subject name and grade value.
Grade Calculator Class (GradeCalculator.java):

Provides static methods for calculating the average grade, letter grade, and GPA.
Methods:
calculateAverage(List<Grade> grades): Calculates the average of the provided grades.
calculateLetterGrade(double average): Determines the letter grade based on the average grade.
calculateGPA(double average): Calculates the GPA based on the average grade.
How It Works
User Interaction:

The user is presented with a menu to choose from different options: adding a grade, calculating the average grade, displaying overall grade information, or exiting the application.
Adding Grades:

The user inputs the subject name and grade value.
The grade is stored in a list for further calculations.
Calculating Average Grade:

The program calculates the average of all stored grades and displays it.
Displaying Overall Grade Information:

The program calculates and displays the average grade, corresponding letter grade, and GPA based on the stored grades.
