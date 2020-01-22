# MustTodoList-server

[MusToDo]

## Intro:

Mustodo is a Node-based Web-App people can use to create, complete and delete self-assigned obligations. We used Mysql with Sequelize to create the server-to-database connection.

## Before Start:

There is a separate github repo for the client file of Mustodo. You must run "npm start" on both client and server files in order for the web-app to run as intended. Make sure you have sequelize-cli and mysql2 installed!

## Dependencies:

body-parser
cors
crypto
express
express-session
morgan
mysql
mysql2
nodemon
save
sequelize
sequelize-cli
Installation:
Just an "npm install" should get you ready to go.

## Functionalities:

### Home page:

Sign up
Log in

### Todo page:

Create todo item
Complete todo item
Delete todo item
Check which todo items were made on which day using the calendar

### My page:

Change account information: username, email, password
Check how many todo items you have created, and how many are complete/incomplete via a donut-chart
Log out
