C File Handling - Academic Project

Project Overview

This repository contains solutions for an academic project on file handling using C programming. The project includes two main functionalities:
	1.	Counting words and converting text content to uppercase.
	2.	Handling employee records with binary file operations.

Each task is implemented in C and adheres to the specifications provided.

Table of Contents

	•	Prerequisites
	•	Task 1: Word Counting and Text Conversion
	•	Task 2: Employee Data Management with Binary Files
	•	Compilation and Execution Instructions
	•	License Information

Prerequisites

To compile and run these C programs, you will need:
	•	A C compiler, such as GCC.
	•	Access to a command line interface.

Task 1: Word Counting and Text Conversion

Word Counting

This program reads a text file (e.g., document.txt) and calculates the number of words present in it. A “word” here is defined as any continuous sequence of alphabetical characters.

Working Mechanism:

	•	Opens the file and reads each character sequentially.
	•	Identifies words by detecting transitions from spaces/punctuation to alphabetic characters.
	•	Outputs the word count upon completion.

Example:

Sample file content: "This is a test."

	•	Expected Output: Total words: 4

Uppercase Conversion

This program reads from a text file (e.g., document.txt), converts all characters to uppercase, and writes the transformed content back to the original file.

Working Mechanism:

	•	Reads each character and applies toupper() to convert lowercase characters to uppercase.
	•	Writes the modified content to a temporary file.
	•	Replaces the original file with the temporary file after conversion.

 Task 2: Employee Data Management with Binary Files

Writing Employee Information

This program collects data for 5 employees (such as email, age, and salary) and stores it in a binary file (employees.bin).

Working Mechanism:

	•	Prompts the user to enter employee details.
	•	Writes the details to a binary file using fwrite() for each employee.

Example Input:

Email: jane.doe@example.com
Age: 28
Salary: 60000.00

Reading Employee Information

This program retrieves and displays employee data from the binary file (employees.bin).

Working Mechanism:

	•	Opens the binary file and reads data using fread().
	•	Prints each employee’s details in a readable format.

Example Output:

Email: jane.doe@example.com, Age: 28, Salary: 60000.00

Compilation and Execution Instructions

Word Counting and Uppercase Conversion

	1.	Save the word counting and uppercase conversion code in files named count_words.c and convert_to_upper.c.
	2.	Compile:

 gcc count_words.c -o count_words
gcc convert_to_upper.c -o convert_to_upper

./count_words
./convert_to_upper

Employee Data Handling

	1.	Save the employee write and read code in write_employees.c and read_employees.c.
	2.	Compile:

 gcc write_employees.c -o write_employees
gcc read_employees.c -o read_employees

./write_employees
./read_employees

License Information

This repository is intended for educational purposes only. Redistribution of this code is prohibited without prior authorization.






