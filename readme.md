git clone https://github.com/patriciooli/delilah3
or download it from Github

Installing dependencies:
npm install
Database Set up:
Auto set up:
Run a MySQL server.

Create the database from MySQL by using the command line or the destktop utility.

Open config.js file (db/sequelize/config.js) where you can edit:

Database's host and port to which the API should connect
Database's name.
Database's user and password to connect.
cd db/db-setup
node index.js

Manual Setup
Initialize the MySQL server.
Create the database called delilah_resto from the command line or the desktop utility.
Create the schema and the tables, and insert the data mannually, by using the queries existing in dbCreators.sql.
Before start using the server, don't forget to edit config.js file (db/sequelize/config.js) with:

Database's host and port to which the API should connect
Database's name.
Database's user and password to connect.
Run the API
 cd server
 node index.js
