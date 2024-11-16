
Melody Moodsync - CS4347-005
============================
Overview
----------------
This project is a song database application developed for CS4347-005 by Lemuel Amouh, Yousuf Stanikzay, Lamisa Tahseen,
Courtney Dickenson, Angelina John, Jahnavi Dhulipalla, Jack Hoggard, Jalay Shukla, and Preston Hern. It utilizes [Python] for application logic 
and MySQL for data storage and management. The application allows users to perform CRUD 
operations on song-related data.

The repository includes all necessary files to set up and run the application.

System Requirements
--------------------
- Node/npm
- git
- MySQLWorkbench

Setup Instructions
------------------

1. **Clone the Repository to the System**
   - ```git clone https://github.com/JacksonHoggard/Song-Database-CS4347-005.git```

2. **Set Up the Database**
   - Open MySQLWorkbench.
   - Run the SQL script to create the database and populate it with the data:
     ```
     source MySQLCreateandPopulate.sql;
     ```

3. **Running the Application**
   - Open 2 command line prompts.
   - On the first command line prompt, navigate to the frontend directory: ```cd Song-Database-CS4347-005/app/frontend```
   - On the second command line prompt, navigate to the backend directory ```cd Song-Database-CS4347-005/app/backend```
   - Type ```npm -v``` to check if npm is installed. If installed, it will show the version you have installed. If not installed, run ```npm install```.
   - Type ```npm start``` on both command line prompts to start the frontend and backend servers.
   - Open ```http://localhost:3000/``` on your browser to run the application.
