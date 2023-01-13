# Forum - internal social network

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

# frontend

 - in the terminal  : npm install
 -  npm run serve
 - App will running at: Local - http://localhost:3000/

#  backend

 - in the terminal cd server
 - npm install
 -  node server
 - Server will running at --8000 
 - Sequelize will connect and the database synced

# Register requirement

 password  contain at least 8 characters including min one uppercase letter, min one lowercase letter and a number, space not allowed.
 
