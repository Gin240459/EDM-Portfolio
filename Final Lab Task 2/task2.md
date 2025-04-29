# Final Lab Task 2: Transforming ER Model to Relational Tables
 # Task Description
 The task is to convert an ER diagram of student assignment submissions into MySQL tables by defining entities and their attributes, establishing relationships, and identifying primary and foreign keys. It also involves accurately representing any dependent or weak entities to create a normalized database schema for effective data management.

# Step by Step
 these are the Steps in order to complete the tasks usigng My SQL Workbench

# Step 1 Create the Student Table
## Student tabale
- username: String (VARCHAR) up to 55 characters.
  
  <img src="https://github.com/Gin240459/EDM-Portfolio/blob/main/Final%20Lab%20Task%202/studentTable.png" alt="Alt Text" width="400" height="300">


# Step 2  Create the Assignment Table
 ## Assignment Table
 - shortname: String (VARCHAR) up to 50 characters.
 - due_date: cannot be NULL
 - url: String (VARCHAR), up to 255 characters, can be NULL.
<img src="https://github.com/Gin240459/EDM-Portfolio/blob/main/Final%20Lab%20Task%202/assignmentTable.png" alt="Alt Text" width="400" height="300">

# Step 3  Create the Submission Table
## Submission Table
- username: String (VARCHAR), up to 50 characters.
- shortname: String (VARCHAR), up to 50 characters.
- version: Integer, represent the version of the submision.
- submit_date: Date, cannot be null.
- data: Text.
<img src="https://github.com/Gin240459/EDM-Portfolio/blob/main/Final%20Lab%20Task%202/submisionTable.png" alt="Alt Text" width="400" height="300">


# ER Diagram or Relational Schema
<img src="https://github.com/Gin240459/EDM-Portfolio/blob/main/Final%20Lab%20Task%202/ERD.png" alt="Alt Text" width="400" height="300">


 # SQL Copy of the Database  ->> [Student Assignment Submission]
