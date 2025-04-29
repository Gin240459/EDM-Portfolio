# Final Lab Task 1 : My Sql Basics-Events Management

This repository contains a set of SQL tasks to be performed using MySQL Workbench. The goal is to practice essential SQL operations such as database creation, table management, data manipulation, and querying. All tasks must be executed in MySQL Workbench and completed in the order specified to maintain proper structure and data relationships.

 # STEP BY STEP:
these steps in order to complete Tasks using MySQL Workbench

## Step 1: Create the Events Table

 ```sql
CREATE DATABASE event_tbl;
USE event_tbl;

CREATE TABLE event_tbl(
event_id INT AUTO_INCREMENT PRIMARY KEY,
event_name VARCHAR(255) NOT NULL);

DESCRIBE event_tbl;
```
___
## Step 2: Create the Attendees table

 ```sql
CREATE TABLE attendees(
attendee_id INT AUTO_INCREMENT PRIMARY KEY,
attendee_name VARCHAR(255) NOT NULL);

DESCRIBE attendee_tbl;
```
___

## Step 3: Create the Event Attendees

 ```sql
CREATE TABLE event_attendees(
event_id INT,
attendee_id INT,
PRIMARY KEY (event_id, attendee_id),
FOREIGN KEY (event_id) REFERENCES event_tbl(event_id),
FOREIGN KEY (attendee_id) REFERENCES attendees(attendee_id));

DESCRIBE event_attendees_tbl;
```
___
## Step 4 : Crete the Event Sponsors 

 ```sql
CREATE TABLE event_sponsors(
sponsor_id INT AUTO_INCREMENT PRIMARY KEY,
event_id INT,
sponsor_name VARCHAR(255) NOT NULL,
FOREIGN KEY(event_id) REFERENCES event_tbl(event_id));

DESCRIBE event_sponsors_tbl;
```
___
 ## ER Diagram or Relational Schema  
 This diagram visually represents the relationships between the tables in the database. It shows how entities like employees, departments, and projects are linked using primary and foreign keys.


# SQL Copy of the Database  ->> [Event Management] 
