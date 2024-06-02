# World Quiz
This repository contains two interactive quizzes built using HTML, CSS, JavaScript, Node.js, and PostgreSQL. The quizzes are designed to test users' knowledge of world capitals and flags.

## Features:
This repo contains 2 Quizzes

## World Capital Quiz:
Users are presented with a series of questions asking for the capital cities of various countries.
After answering, they receive immediate feedback on whether their answer was correct or not.
Users can track their progress with a score counter.
The quiz is dynamically generated from data stored in a PostgreSQL database.

## Flag Quiz:
Users are shown images of flags from different countries.
They need to guess the country associated with each flag.
Similar to the World Capital Quiz, users receive instant feedback and can track their score.
The quiz retrieves flag images and country data from the PostgreSQL database.

## TechStack:
Frontend: HTML, CSS, JavaScript.
Backend: Node.js.
Database: PostgreSQL.

## Setup Instructions:
1. Clone the repository to your local machine.
2. Install Node.js if not already installed.
3. Set up a PostgreSQL database and run slq query from `queries.sql`
4. import the provided csv data from `capitals.csv`, make sure to check **Headers** in option menu while importing csv.
5. Configure the database connection in the `index.js` application (change database, password with your own).
6. Install node_modules using `npm install`.
7. Run the `index.js` using `node index.js`.
8. Open the quizzes in your web browser (localhost:3000) to start playing.
