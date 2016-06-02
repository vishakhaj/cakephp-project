-- Job Board --

-Server used is xampp server. 
If you are using xampp server, place the directory in xampp->htdocs->directory_name
If you are using wamp server, place the directory in wamp->www->directory_name

-Create database in mysql (localhost/phpmyadmin)

-Create table 'jobs' in database 'job_board'

-Query for creating the table is as follows:-

CREATE TABLE jobs(
id INT AUTO_INCREMENT PRIMARY KEY ,
company VARCHAR( 50 ) ,
type_of_work VARCHAR( 50 ) ,
city VARCHAR( 50 ) ,
job_description TEXT,
email VARCHAR( 255 ) ,
token VARCHAR( 255 ) ,
created DATETIME,
modified DATETIME
);

-Rename database.php.default to databasae.php and changed the username, password, database name to your own credentials

-Change the Security and Cipherseed values in core.php

-Once you are done with the above instructions, Cakephp is configured and installed.

-Include bootstrap for styling 

-Follow the MVC model to develop the cake php application(refer the code)

-Run the application: localhost/directory_name (in this case, localhost/jobboard) 

