# Student-Statistics

## Description

A RESTful API for managing student data, including student information and assignments. This project allows you to perform CRUD (Create, Read, Update, Delete) operations on students and their assignments, providing an efficient way to manage student statistics.

## Table of Contents (Optional)


- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation

To setup this project, follow these steps:

1. Clone the repository https://github.com/Mekenna-Baker/Student-Statistics
2. Navigate to the repostiory on your local machine
3. Run an npm install in your terminal to install dependencies
4. Make sure you have MongoDB installed on your local machine, and start the server by running 'npm run start' in your terminal
5. Seed the database by running 'npm run seed'


## Usage

To use the API you can test the endpoints with Insomnia. Here are some examples of how the interact with the API: 

Get all students: GET /api/students/
Get student by ID: GET /api/students/:studentId
Create new student: POST /api/students
Add an assignment: POST /api/students/:studentId/assignments
Update Student Information: PUT /api/students/:studentId
Delete a student: DELETE /api/students/:studentId
Delete an assignment: DELETE /api/students/:studentId/assignments/:assignmentId


