# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS

## Date:
## AIM:
To create a student database and execute DDL queries using SQL.


## DDL (Data Definition Language)
<div align="justify">
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
</div>
 
## List of DDL commands: 
<div align="justify">
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
DROP: This command is used to delete objects from the database.
ALTER: This is used to alter the structure of the database.
TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
RENAME: This is used to rename an object existing in the database.
</div>

## Query:
### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.

### SQL QUERY: 
create table student(rollno int, name char(20), age int, address varchar(20), phoneno int);

### OUTPUT:

![WhatsApp Image 2023-09-29 at 20 48 29](https://github.com/niraunjana/G2_DBMS/assets/119395610/aee84216-b2d8-4542-8964-d1777239369d)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
alter table student add department char(30)

### OUTPUT:

![WhatsApp Image 2023-09-29 at 20 48 54](https://github.com/niraunjana/G2_DBMS/assets/119395610/eb1cd98d-860f-4ffd-befc-37a3e2bc6b4b)



### 3) Drop the student table
 
### SQL QUERY: 

drop table student;


### OUTPUT:

![WhatsApp Image 2023-09-29 at 20 49 18](https://github.com/niraunjana/G2_DBMS/assets/119395610/f353625d-b2f5-4d68-b661-6cc24bf9cd31)


### 4) Delete the student table using truncate keyword

### SQL QUERY: 

truncate table student


### OUTPUT:

![WhatsApp Image 2023-09-29 at 20 49 43](https://github.com/niraunjana/G2_DBMS/assets/119395610/51d9e06c-6cf1-4cbc-9dc7-9c1482631733)



### 5) Rename the student table to mystudent

### SQL QUERY: 

alter table student rename to mystudent;


### OUTPUT:

![WhatsApp Image 2023-09-29 at 20 50 07](https://github.com/niraunjana/G2_DBMS/assets/119395610/f115e277-e36d-4828-80b1-b384496918dd)

### Result :

To create a student database and execute DDL queries using SQL is executed successfully.

