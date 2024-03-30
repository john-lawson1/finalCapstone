# finalCapstone (BYB5 - Compulsory Task 2)

## Overview
This program is a **Task Manager** for any number of registered users to create and manage a list of tasks. Reports can also be run on screen or saved to files to display user and task statistics. 

It was created and submitted for Task 17 of the HyperionDev Software Engineering Fundamentals course (Cohort 6).

It has been added to Github as part of Task 21 (Compulsory Task 2) to demonstrate the loading of a project onto Github and the documentation of a Readme file.

## Table of Contents
1. [Installation](#installation)
3. [Usage](#usage)
4. [Screenshots](#screenshots)
5. [Credits](#credits)

## Installation
- Ensure you open the whole folder for this task in VS Code otherwise the program will look in your root directory for the text files.
- A default 'admin' username and password is created automatically by the program, which should be restricted for use by the program administrator to access the admin rights:
  - username: admin
  - password: password

- The Task Manager program uses the following inbuilt Python modules/methods:
  - os
  - datetime, date from datetime

##  Usage
A User, who is not the administrator, must first be registered with a username and password, which they can then use to log in to the Task Manager. 

The Task Manager program has the following functionality:
- The user is required to log in with a valid username and password
- The user is presented with a MAIN MENU with the following options:
  - ru - Register a user
  - at - Add a task
  - va - View all tasks
  - vm - View my task
  - gr - Generate reports
  - ds - Display statistics (admin user only)
  - ex - Exit

- The 'vm' option allows users to choose a task to edit
- The user is presented with an EDIT MENU with the following options:
  - tc - Mark task as complete
  - ua - Edit user assigned to task
  - dd - Edit task due date
  - ex - Exit to Main Menu



## Screenshots
Login and MAIN MENU

![image1](https://github.com/john-lawson1/finalCapstone/assets/80202595/0542022a-68ab-4500-87f7-195ae946753e)

Adding a task

![image2](https://github.com/john-lawson1/finalCapstone/assets/80202595/846615c4-cccf-4f0e-8bac-7a9f572a6b0a)

View my tasks

![image3](https://github.com/john-lawson1/finalCapstone/assets/80202595/38acb8ac-2fe6-4cca-8f74-5ce072210b36)

Edit a task

![image4](https://github.com/john-lawson1/finalCapstone/assets/80202595/a30ab084-2258-498d-aded-aa650246ae2a)

Display stats on the screen

![image5](https://github.com/john-lawson1/finalCapstone/assets/80202595/def26f66-bc83-4829-bca7-c012225ae6cc)

Task overview file

![image6](https://github.com/john-lawson1/finalCapstone/assets/80202595/f5fc40ca-9bcc-41ac-828c-42f7e3785123)

User overview file

![image7](https://github.com/john-lawson1/finalCapstone/assets/80202595/56060f3a-1139-4994-b5ef-2c2a9d7d0376)


## Credits
I would like to thank HyperionDev for their support through their helpful review of my submission of this program as part of the Software Engineering Fundamentals course.
