# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS
## DATE: 03/08/2023
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
create table student(rollno int,name char(20),age int,addr varchar(20),phoneno int);
### OUTPUT:
![270707363-490a6bfd-05f1-4789-8526-274d786999c9](https://github.com/AdhithyaMR/G2_DBMS/assets/118834761/b78f9e1e-cbcf-434f-b62a-fb42922aeed1)
### 2) Change the above student table by adding another attribute department
### SQL QUERY: 
alter table student add department char(30);
### OUTPUT:
![270707453-9ee913f2-a82f-4b3d-a2bb-d5f2254184d1](https://github.com/AdhithyaMR/G2_DBMS/assets/118834761/27044e69-3717-49c7-9be6-e34f217cf661)
### 3) Drop the student table
### SQL QUERY: 
drop table student;
### OUTPUT:
![270707545-fbbd4d76-7f7f-4a96-876d-ea3f7688a81f](https://github.com/AdhithyaMR/G2_DBMS/assets/118834761/b562d2da-f918-4772-9e3d-216fd601ded3)
### 4) Delete the student table using truncate keyword
### SQL QUERY: 
truncate table student;
### OUTPUT:
![270707630-a588479f-0b33-4e5a-88cd-e8b2e2069a77](https://github.com/AdhithyaMR/G2_DBMS/assets/118834761/36a3b6d0-9a38-425a-89c9-37e90fa30b1c)
### 5) Rename the student table to mystudent
### SQL QUERY: 
alter table student rename to mystudent;
### OUTPUT:
![270707720-0c723764-5e0e-49ce-927b-b1fdd0a03f66](https://github.com/AdhithyaMR/G2_DBMS/assets/118834761/23e2e7b7-12f4-4670-b8e9-5da2f1576df8)
## RESULT:
To create a student database and execute DDL queries using SQL is executed successfully.




