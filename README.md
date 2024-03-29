# Online Quiz Java Project

This is a command-line based online quiz project implemented in Java using object-oriented programming concepts. It uses MySQL as the database for storing quiz questions, answers,instructions and user information like teacher details and student details.

## Features

- Teacher authentication: Allows Seacher to log in and give the quiz to students.
- Student authentication: Allows Students to log in and take the quiz.
- Quiz management: Supports adding, editing, and deleting quiz questions.
- Instruction management: Supports adding, editing, and deleting Instructions for Students.
- Score tracking: Tracks and displays user scores for each quiz.

## Prerequisites

- Java Development Kit (JDK)
- MySQL Server
- MySQL Connector/J (JDBC driver for MySQL)

## Database design

- In the quiz_database_design.txt file there are commands to create a database according to this project.

## Overview

- project_blue_print.txt will provide a basic blue print and over view of how this project works in the command line.


## Commands to run the project:

while running the project , current directory should be './src' then run the below commands to run this project.

### To compile the project, use the following command:

- javac -d ./classes CSV/*.java javaProject/*.java

#### To run the project, use the following command:

- java -cp "mysql-connector-j-8.3.0.jar;./classes" javaProject.Main  

1st command will compile all java files in the project and it will store that class files in classes folder.

2nd command will run the Main class file.

