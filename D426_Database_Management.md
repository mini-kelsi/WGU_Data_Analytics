## 1.1 Database Basics

*Database Application  
   -Software that helps business users interact with database systems.
 
*Database Adminnistrator  
    -Responsible for securing the database system against unauthorized users. Enforces procedures for user access and database system availability.

___________________________________________________

## 1.2 Database Systems
___________________________________________

*Authorization   
    -Many database users should have limited access to specific tables, columns, or rows of a database.
Database systems should authorize individual users to access specific data.

*Rules    
     -Database systems ensure data is consistent with structural and business rules.
     
*Query Processor    
     -The query processor interprets queriers, creates a plan to modify the database or retrieve data, and returns query results to the application.

*Storage Manager     
     -The sotrage manager translates the query processor instructions into low-level file commands that modify or retrieve data.
     
*Transaction Manager     
     -Ensures transactions are properly executed.     
     -**Writes logs before applying changes to the database.**
*Metadata     
     -Data about the database, such as column names and the number of rows in each table.
     
*Relational Database     
     -Stores data in tables, columns, and rows
     -Similar to a spreadsheet
     
*Relational databases are good for?     
     -Ideal for databases that require an accurate record of every transaction, such as banking, airline reservation systems, and student records.
     
*SQL     
     -Structured Query Language and includes statements that read and write data, create and delete tables, and administer the database system.
     
*Big Data     
     -Growth of the internet int he 1990s generated massive volumes of onlinen data, called big data, often with poorly structured or missing information.
     -MongoDB:Big Data, open source, NoSQL
     
*NoSQL     
     -The newer non-relational systems are called NoSQL, for 'not only SQL', and are optimized for big data.
     MongoDB: Big Data, open source, NoSQL
_______________________________________________________________

## 1.3 Query Languages
___________________________________________________

*INSERT     
     -inserts rows into a table.

INSERT INTO table_name (column_name1, column_name2, ...)
                      VALUES (DEFAULT, 'bob', 30, 150);

*SELECT     
     -retrieves data from a table

SELECT column1, column2, ...
FROM table_name; -- return all data from those columns.

*UPDATE     
     -modifies data in a table
UPDATE table_name
SET   column_name = 2
WHERE column_id = 3;

*DELETE     
     -Deletes rows from a table.

DELETE FROM table_name; -- all rows deleted!
DELETE FROM table_name WHERE column_name = 'value'; -- delete row

*CREATE TABLE     
     -Creates a new table by specifying the table and column names.

CREATE TABLE Customers (
  customerId    INT NOT NULL UNIQUE,
  first_name    VARCHAR(255) NOT NULL,
  age           INT CHECK(age > 18)
  driverid      INT NOT NULL,
  PRIMARY KEY (customerId),
  FOREIGN KEY (LOCAL_COLUMN_NAME) REFERENCES TABLE_NAME (COLUMN_NAME),
);

______________________________________________________________

## 1.4 Database Design and Programming
_________________________________________

*Database Design: **Analysis**     
     -Specifies Databases requirements without regards to a specific database system.
     -Requirements are represented as entities, relationships, and attributes.
     -Sometimes called: Conceptual Design
     
*ER Diagram     
     -Entities, relationships, and attributes are depicted in ER diagrams.
     
*Database Design: **Logical Design**     
     -This phase implements database requirements in a specific database system.     
     -For relational database systems, logical design converts entities, relationships, and attributes into tables, keys and columns.
     -**The logical design is called a database schema.**

*Key     
     -A column used to identify individual rows of a table.
     -Tables, keys, and columns are specified in SQL with CREATE TABLE statements.

*Database Design: **Physical Design**     
     -This phase adds indexes and specifies how tables are organized on storage media.
     -**Physical Design affects query processing speed but NEVER affects the query results.**

*Data Independence     
     -Principle that phyiscal design enver affects query results.
     -When database designers modify indexes or row order, applications run faster or slower but always generate the same results.

*Application Programming Interface/ API     
     -simplify the use of SQL with a general-purpose language.
     -An application programming interface, or API, is a library of procedures or classes that links a hosts programming language to a database.

## 1.5 MySQL

*MySQL Command-Line Client     
     -A text interface **included** in the MySQL Server download.
     -Allows developers to connect to the database server, perform administrative functions, and execute SQL statements.
     -MySQL Community sometimes includes the 'world' database, a database to practice with.
     
## 2.01 Relational Model

*Relational Database     
     -A database model is a conceptual framework for database systems, with three parts:     
          -*Data structures*: that prescribe **how data is organized.**      
                    >data structures form the backbone of efficient and organized information storage.     
                    >Each database model relies on specific structures to represent entities, attributes, and relationships, ensuring data integrity and facilitating smooth retrieval and manipulation.     
                    >e.g. relational model: primary key, foreign key, data types (INT, STRING, ...) indexes     
               -*Operations*: that **manipulate data structures**     
            -*Rules*: logical constraints that ensure the **data is valid**     

*Set     
     -Is an **unordered** collection of elements enclosed in braces.
     -e.g. {a, b, c} and {c, b, a} are the same, since sets are **not** ordered.     

*Tuple     
     -An **ordered** collection of elements enclosed in parentheses.
     -e.g. (a, b, c) and (c, b, a) are different, since tuples are ordered.     

*Table     
     -Has a name, a fixed tuple of columns, and a varying set of rows.
     -Synonyms:Table, File, Relation.     

*Column     
     -Has a name and a data type.     
     -Synonyms: Column, Field, Attribute.     

*Row     
     -Is an unnamed tuple of values. Each value corresponds to a column and belongs to the column's data type.     
     -Since rows are a set, rows have no inherit order.     
     -Synonyms: Row, Record, Tuple     

*Relational Data Type     
     -A data type is a named **set of values**, from which column values are drawn.     

*Relational Rules     
     -Rules are **logical contraints** that ensure data is valid.     
     -Are part of the relational model and govern data in every relational database.     

*Relational Operations     
     -SELECT     
     -JOIN     
     -UNION     
     -AGGREGATE     

*Business Rules     
     -Rules are logical contrainst that ensure data is valid.     
     -Business rules are based on business plicy and specific to a particular database.     
     -e.g. All rows of the 'Employee' table must have a valid entry in the 'DepartCode' column.     

## 2.02 Structured Query Language

*Structured Query Language/ SQL     
     -A **high-lvl computer language for storing, manipulating, and retrieving data.**     
     -Standard language for **relational databases**, and is commonly supported in non-relational databases.     

*SQL Statement Literals: Strings, Numbers, Binary     
     -Explicit values that are string, numberic, or binary.     
      -Strings must be surrounded by single quoutes or double quotes     
      -Numberic     
      -Binary vlaues are represented with x'0' where the 0 is any hex value.     

***Data Definition Language**     
     -(DDL) defines the structure of the database.     
     -*CREATE, ALTER, DROP*     

***Data Manipulation Language**     
     -(DML) manipulates data stored in the database.     
     -*INSERT, UPDATE, DELETE*     

*Data Query Language     
     -(DQL) Retrieves data from the database.     
     -SELECT     

*Data Control Language     
     -(DCL) Controls database user access     
     -GRANT, REVOKE     

*Data Transaction Language     
     -(DTL) manages database transactions.     
     -SAVEPOINT, ROLLBACK, COMMIT     

## 2.04 Tables

*Table     
     -Has a name, a fixed sequence of columns(tuple) and a varying set of rows)     

*Table Rules     
     -Exactly one value per cell.  A cell may not contain multiple values. Unknown data is represented with a special NULL value.     
     -No duplicate column names. Duplicate column names are allowed in different tables, but not in the same table.      
     -No duplicate rows. No two rows may have identical values in all columns.     
     -**No row order.** Organization of rows on a storage device never affects query results.     
*CREATE TABLE     
     -DDL     
     -Creates a new table by specifying the table name, column names, and column data types.     
*DROP TABLE     
     -DDL     
     -Deletes a table, along with all the table's rows, from a database.     
     -DROP TABLE Tablename;     

*ALTER TABLE     
     -DDL     
     -Adds, Deletes, or modifies columns on an existing table.  

-- Add Column and data type.
ALTER TABLE TableName
  ADD ColumnName DataType;
-- Change Column Name and data type.
ALTER TABLE TableName
  CHANGE CurrentColumnName NewColumnName NewDataType;
-- Drop Column
ALTER TABLE TableName
  DROP ColumnName;

## 2.05 Data Types     


*Data Type     
     -A data type is a named set of values from which column values are drawn.     
     -INT -- Positive and ngeative integer values.     
     -VARCHAR(N) -- values with 0 to N characters.     
     -CHAR(N) -- Fixed string value, if string is less than stated, space padding will be added.     
     -DATE -- date values YYYY-MM-DD     
     -TIME -- hh:mm:ss     
     -DATETIME -- YYYY-MM-DD HH:MM:SS     
     -DECIMAL(N,D) - numeric values with total N didgits of which D digits follow the decimal point.
