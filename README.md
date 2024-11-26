# Task-Master
My final 3MTT capstone project

### Database setup
## Create a database called taskman
~~~
CREATE DATABASE taskman
~~~
- Copy and paste the query above on your PHPmyAdmin query box and run to create the database for taskmaster.

### Extracting files
- Extract the files from the zip folder that you have downloaded
- Import the SQL files you have extracted form the PHPmyAdmin
- Extract the taskmaster files from the zip folder to the location of your choice 

### Code database connection
## Open homeController.js from the controllers folder in the file you extracted
- Replace your database pool connection string with the following details
~~~
"host": "localhost",
"user": "root",
"password": "",
"database": "taskman"
~~~

## Open taskController and replace the database pool connection with the above details
- Run your program from cmd or powershell
