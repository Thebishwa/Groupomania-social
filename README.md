# Forum - internal social network

Download the repository and follow the instructions below to install this project locally

# Required

 - Node.js
 - Vue.js
 - MySQL

# MySQL database

 - From MySQL Workbrench setup a new connection
 - Type a name for the connection
 - Add two parameters : username and password
 - Create a new database called 'forum'

 - Open main folder and go to server/src/sequelize/config/config.json
 - In config.js on development option write your username and password previously chosen

# Installing and starting frontend

 - Open your terminal and go to main folder
 - Install all dependencies: npm install
 - Start the application: npm run serve
 - App will running at: Local - http://localhost:3000/

# Installing and starting backend

 - Open your terminal and the main folder and go to server
 - Install all dependencies: npm install
 - Start the application: node server
 - Server will running at --8000 
 - Sequelize will connect and the database synced

# Register requirement

 password  contain at least 8 characters including min one uppercase letter, min one lowercase letter and a number, space not allowed.
 