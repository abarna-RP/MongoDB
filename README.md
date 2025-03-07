# Zen Class Program Database and Queries

This repository contains the MongoDB database design and queries for a Zen Class program.

## Database Design

The database `zen_class` consists of the following collections:

* **users:** Stores user information.
    * `_id`: User ID (Number)
    * `name`: User's name (String)
    * `email`: User's email (String)
    * `mentor_id`: ID of the mentor assigned to the user (Number)
    * `company_drive_appeared`: Array of company drive IDs the user has appeared for (Array of Numbers)
* **codekata:** Stores codekata problem-solving data.
    * `user_id`: User ID (Number)
    * `problems_solved`: Number of problems solved by the user (Number)
* **attendance:** Stores user attendance records.
    * `user_id`: User ID (Number)
    * `date`: Attendance date (Date)
    * `present`: Attendance status (Boolean)
* **topics:** Stores information about topics taught in the program.
    * `_id`: Topic ID (Number)
    * `topic`: Topic name (String)
    * `month`: Month the topic was taught (Number)
    * `year`: Year the topic was taught (Number)
* **tasks:** Stores user task information.
    * `user_id`: User ID (Number)
    * `task`: Task description (String)
    * `due_date`: Task due date (Date)
    * `submitted`: Task submission status (Boolean)
* **company_drives:** Stores company drive information.
    * `_id`: Company drive ID (Number)
    * `company`: Company name (String)
    * `date`: Company drive date (Date)
* **mentors:** Stores mentor information.
    * `_id`: Mentor ID (Number)
    * `name`: Mentor name (String)
    * `mentee_count`: Number of mentees assigned to the mentor (Number)
above images contain queries details .....
![alt image](https://github.com/abarna-RP/MongoDB/blob/8ffb8ba22d0e32b0b080448eab5864d2a338d5bf/collection%20img.png)
