# cookbook



## Where is the project

our project is in main and to get it going there are somethings that need to be handled.

## database connection
Our database has a connection in multiple spots. the easiest way to get it up and running is to batch replace the following:
1- "jdbc:mysql://localhost:3306/cookbook" with the url where your database is located
2- "root" with your username
3- "toor" with your password

Other than that our database structure is in the Database folder these are all sql scripts. 
In sql go to server -> data import and import the database folder this will create and populate a version of our database.

## Process
The proces we went through isn't extremely well documented but can be found at the following link: https://drive.google.com/drive/folders/1hYqzOZ2nyeIm9ttCU_Olud5o30KNwQhC?usp=sharing To view this link please use an account connected to the university.