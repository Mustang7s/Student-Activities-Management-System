# Student-Activities-Management-System
**Student Activities Management System
This is a command-line-based Student Activities Management System implemented in C++ by [My GitHub Profile](https://github.com/Mustang7s)  

. It allows users to manage students, assign them to sports and clubs, view student details, and save data to a CSV file.

# Features
Add Student: Add students with details such as name, gender, age, group, sports, and clubs.
View Students: Display all students along with their assigned sports and clubs.
View Grouped Students: Display students grouped by their BBIT groups.
View Activities: Display available sports and clubs with their capacities and current member counts.
Save All Files: Save all student data to a CSV file named students.csv.
Implementation Details
# Language
C++
Codeblock Compiler
# Main Libraries
# iostream

Functions: Provides basic input and output services for C++ programs.
Usage: Used for console input (cin) and output (cout) operations.
vector

Functions: Implements a dynamic array that can grow or shrink in size.
Usage: Used to store collections of students, activities (sports and clubs), and their details dynamically.
string

Functions: Provides a standard string class for manipulating strings.
Usage: Used for storing and manipulating student names, genders, club names, etc.
# fstream

Functions: Provides classes to read from and write to files as streams of bytes.
Usage: Used to save student data into a CSV file (students.csv) and potentially load data from files in future expansions.
# cstdlib

Functions: Provides several general-purpose functions in C++.
Usage: Specifically used for rand() and srand() functions to generate random numbers for simulating student data.
# ctime

Functions: Provides functions to manipulate date and time information.
Usage: Used with time() function to seed the random number generator (srand(time(0))), ensuring different random sequences on each program execution.

# Files
main.cpp: Contains the main logic of the application.
students.csv: CSV file for storing student data.
