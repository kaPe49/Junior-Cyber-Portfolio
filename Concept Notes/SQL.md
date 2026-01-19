# SQL Fundamentals
**Databases** hold **tables** that use **rows** and **columns** to store information. **SQL** is the language used to interact with relational databases.

## Syntax
`CREATE` is used to create a database and specify its name  
Example: `CREATE DATABASE my_database;`  

`SHOW` is used to list all your databases  
Example: `SHOW DATABASES;`  

`USE` is used to specify which database you will interact with  
Example: `USE my_databse;`  

`DROP` is used to delete a database  
Example: `DROP my_database;`  

### Table Statements
`CREATE TABLE` is used to create a table within a database and specify its columns and the data type of those columns  
Example:  
`CREATE TABLE my_table (`  
`id INT PRIMARY KEY,`  
`name VARCHAR(255),`  
`date DATE`  
`);`  

`DESCRIBE`  

### CRUD Statements
