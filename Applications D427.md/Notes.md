### Section 1

## 1.1 Relational Model

- Database Model
  A conceptional framework for database systems with three parts
  1. Data Structures : Prscribe how data is organized
  2. Operations : Manipulate data structures.
  3. Rules : Govers valid data

- Relational Model
  - Database model based on a tabular data structure
  - Initially designed for transational data

**Which database is relational?**

 **-Oracle Database**

 **The relational model was orinally developed for which type of applications?**
  
   **-Transactional applications like banking and airline reservations.** 

  **What was the initial impediment to commerial adoption of relational database in the early 1980s?**
  
   **-Processing speeds**

- Big Data
  - Characterized by unprecedented data volumes and rapidly changing data structures

- Set
  - An unordered collection of elements enclosed in braces {}

- Tuple
  - An ordered collection of elements enclosed paratheses ()

**Which terms are commonly used in database processing?**
 
  **-Row, table, column**

**In the relational data structure, which components are named?**
 
  **-Data type, table, column**

**Can a query select on specific row from a table?**
 
  **-Yes, by specifiying one or more row values**

**What is the result of a relational operation?**

  **-A table**

**Name three relational operations.**

  **-Select, project, and union**

**An SQL statement can implement only one relational operational.**
  **-False**

- Relational Rules
  - Are part of the relational model and govern data in every relational database. EX.
    - Unique primary key
    - Unique column names
    - No duplicate rows

- Business Rules
  - Based on business policy and specific to a particular database

**Unique primary key is an example of a relational rule.**

  **-True**

**Delete cascade is an example of a relational rule.**
 
  **-False**

**Data in a relational database can violate relational rules.**
 
  **-True**

**SQL commands can create databases and tables.**

  **-True**

**All database systesm use identical SQL statements.**

  **-False**

| Mathmatics | Databases |      
|  :------:  |  :-----:  |      
| Attribute  | Column    |      
|  Domain    | Data Type |      
| Relation   | Table     |      
| Tuple      |   Row     |

 | File Systems | Databases |
 |   :------:   |  :------: |
 | Field        | Column    |
 | File         | Table     |
 | Record       | Row       |
 | Data Type    | Data Type |
 
- SQL Statement
  - A complete command composed of one or more clauses

- Clause
  - Groups SQL keywords like SELECT, FROM, and WHERE with table names, column name and condition

**The INSERT statment adds a student to the student table. How many clauses are in the INSERT statement?**
 
  **-2**

**The SQL statement below is uses to select student s with the last name "Smtih". What is wrong with the statement?**
>SELECT FirstName

>FROM Student

>WHERE LastName = Smith;

 **-The literal "Smith" must be surrounded by single quotes or double quote**

**What is wrong with the SQL statement below?**
>SELECT FirstName

>--From Student

**-The FROM clause is a comment.**

---------------------------------------------------------

### SQL Sublanguages

- Data Definition Lang (DDL)
  - Defines the structure of the database
  - creates, alters, drops tables

- Data Query Lang (DQL)
  - Retrieves data from the database
  - selects data from tables

- Data Manipulation Lan (DML)
  - Manipulates data stored in a database
  - inserts, updates, deletes

- Data Control Lang (DCL)
  - Controls database user access
  - grants, revokes access to & from users

- Data Transaction Lang (DTL)
  - Manages database transactions
  - commits data, rollbacks, savepoints

--------------------------------------------

- Database system instance
  - A single executing copy of a database system
  - *Personal computer* usually run one instance
  - *Shared computer* usually runs multiple instances

- SHOW statement provides info about databases, database contents (tables, columns, etc), and server status

- Common SHOW statements
  - SHOW DATABASES
    - list databases avaliable in the system
  - SHOW TABLES
    - list tables avaliable in currently selected database
  - SHOW COLUMNS
    - list columns avaliable in a specific table
  - SHOW CREATE TABLE
    - shows the create table statement for a given table

- USE statement selects a database and is required to show infor about tables within a sepcific database.

**Which statement shows all databases in a database system?**
  
  **-SHOW DATABASES;**

**Which statement shows all tables in database petstores?**
  
  **-SHOW TABLES;**

**Which statement must preced a SHOW TABLES statement to see the tables from the bikeStore database?**

  **-USE bikeStore;**

**Which statement shows all the columns in the Country table?**

  **-SHOW COLUMNS FROM Country;**

- A table must have at least one column but any number of rows. A table without rows is called an *empty table.*

**Which choice is a column name?**
  
  **- Salary**

**Which choice is a cell name?**
  
  **-30500**

**What are the components of a column?**

 **-Name & data type**

**Must a table have at least one row?**
 
  **-No**

**How does a database administrator specify column names & data types?**
  
  **-With the SQL Language**

- Rules governing tables
  - Exactly one value per cell
  - No duplicate column names
  - No duplicate rows
  - No row order

- Rule 4 is data independence.

**___ may appear in each cell.**
  
  **-Exactly one value**

**Where are duplicate column names allowed?**
  
  **-in different tables**

**What does the principle of data independence state?**

  **-The result of a database query is not affected by the phsyical organization of data on storage devices.**

**How can driver's license information be added to the employee table?**
  
  **-By creating, another column with a new name, such as ID2, or DriverLicense.**

- DROP TABLE
  - Deletes a table, along with all table rows, from a dataset

>ADD -> Adds a column

>CHANGE ->Modifies a column

>DROP ->Deletes a column

**Add a column caled Description to the Department table.**

>ALTER TABLE Department

>ADD Description VARCHAR(50);

**Rename column Description to ShortDesc.**

>ALTER TABLE Department

>CHANGE Description ShortDesc VARCHAR(50);

**Change column ShortDesc to accept up to 80 characters.**

>ALTER TABLE Department

>CHANGE ShortDesc ShortDesc VARCHAR(80);

**Delete the column ShortDesc.**

>ALTER TABLE Department

>DROP ShortDesc;

**A binary data type stores data as an exact copy of computer memory.**
  **-True**

**Some dat & time data types include time zone.**
  **-true**

- *Signed number*
  - may be negtive

- *Unsigned number*
   - **cannot** be negative

- **Operator** is a symbol that computes a value from one or more values (called operands)

- *Unary* operatory has one operand.

- *Binary* operator has two opertors.

|Logical Operators | Arithmetic Operators |Comparison Operators |
|  :----:     |  :----:    | :----: |
|AND | + | = |
|OR | - | != |
|NOT | * | <>|
|   | / | < |
|   | % | > |
|   | ^ | <= |
|   |  | =>  |


- Expression is a string of operators, oprads & parentheses that evaluates to a single value.

- SQL has a **LIMIT** clause that limits the number of rows returned by a select statement.

- A condition is an expression that evaluates to a logical value.

- A SELECT statement has an optional **WHERE** clause that specifies a condition for selection of rows.

- NULL values represent either unknown or inapplicable data.

- Optional **DEFAULT** keyword & default value follow the column name and data type in a  **CREATE TABLE** statement.

- **UPDATE** statement modifies exsisting rows in the table.

- The **UPDATE** statement uses the **SET** clause to specify the new column values.

>UPDATE Song

>SET Title = 'With or Without You'

>WHERE ID = 200;

- **TRUNCATE** statement deletes all rows from a table

- *Simple Primary Key* consist consist of a single column.

- *Composite Primary Key* consist of multiple columns.
   - denoted with parentheses

- **RESTRICT** rejects an insert, update, or delete that violates referential integrity.

- **SET NULL** set invalid foreign keys to NULL

- **SET DEFAULT** sets invalid foreign keys to the foreign keys default value

- **CASCADE** propagates primary key changes to foreign key

- **CHECK** constraint specifics an express on one or more columns of a table

- **CONSTRAINT** name the primary key table constraint

>CREATE TABLE Department(

>Code INT,

>Name VARCHAR(20),

>Manager ID INT,

>CONSTRAINT Department Key

>Primary Key(Code)

>);

- Name the check column constraint 'Check Manager'

>CREATE TABLE Department(

>Code INT,

>Name VARCHAR(20),

>Manager ID INT, *Constraint Check Manager*

>*Check(ManagerID>999)*,

>Primary Key(Code));

- Add a UNIQUE constraint called UniqueNameMgr that ensures the name & manager Id combo are unique.

>CREATE TABLE Department (

>Code TinyINT Unsigned,

>Name VARCHAR(20),

>ManagerID SmallINT,

>*Constraint UniqueNameMgr Unique(Name, ManagerID)*,

>Primary Key(Code));

- Constraints are added & dropped with the **ALTER TABLE table_name** followed by add, drop, or change clause.

- Unnamed constrains such as NOT NULL & DEFAULT are added or dropped with a change clause.

# Section 2

>ALTER TABLE Department

>*CHANGE* Salary Salary INT Not Null;
------
>ALTER TABLE Department

>*ADD* Constraint MgrIDCheck CHECK;
------
>ALTER TABLE Department

>*Drop* Index Unique NameMrg;
------

- IN operator is used in a WHERE clause to determine if a value matches one of several values.
- BETWEEN operator provides an alternative way to determine if a value is between two other values.
- JOIN  statement that combines data from 2 tables.

**Tables must have comparable data types.**

- The first table in the FROM clause of a join statement is called the *Left table*.  The second table is the *right table*.
- INNER JOIN selects only **matching** left & right table rows.
- FULL JOIN selects ALL left & right table rows *regardless of match*
- LEFT JOIN selects ALL left table rows, but *only matching* right table rows
- RIGHT JOIN select ALL right table rows but *only matching* left table rows
- OUTER JOIN is any join that selects unmatched including left, right and full joins
- UNION combines the two results into one table

--------------

- EQUIJOINS compares columns with the = operator
- NON-EQUIJOINS compares columns with an operator other than =, like > and <.
- 
  **Most joins are equijoins**

- SELF JOIN joins a table to itself
- CROSS JOIN combines two tables without comparing columns

  **All possible combos of rows from both tables appear in the result**

- Nested query (or supery/inner query) is a query within another SQL query.
  **Usually in the statements WHERE clause in ().**

- EXIST operator returns TRUE if a subquery selects *atl least one* row and FALSE *if no rows* are selected.
- NOT EXIST returns TRUE if a subquery selects *no rows* and FALSE if *at least one* row is selected.
- Replacing a subquery with a join equialvent is called **Flattening** a query.

#Steps are a frist pass at flattening query:# 
1. Retain the outer query SELECTG, FROM, GROUP BY, HAVING and ORDER BY clauses.
2. Add INNER JOIN clauses for each subquery table.
3. More comparison between subquery table.
4. Add a WHERE clause with the remaining expressions in the subquery and outer quere WHERE clauses.
5. If necessary, remove duplicate rows with SELECT DISTINCT.

**After this first pass, test the flattened quesry and adjust to achieve the correct result. Verify that the orginial and flattened queries are  equivant against a varity of data.**

- VIEW TABLE is a table name associated with SELECT statement, called the *view query*.
- CREATE VIEW statement creats a view table & specifies the view name, query  and optionally, column names.

>CREATE VIEW ManagerView

>AS SELECT DepartmentName, EmployeeName,

>AS ManagerName

>FROM Department, Employee

>WHERE ManagerID = EmployeeID;

- A table specified in the view query's FROM  clause is called a *base table*.
- **Materialized view** is a view for which data is sotred at all times.

- Advantages of views
  - Protects sensitive data
  - Save complex data queries
  - Save optimized queries

**Using materialized views always imporves database performace.**

  **-False**

**The performance of a user query on a view is indentical to the performance of the corresponding merging query on base tables.**

  **-True**

**A view query can reference another view table.**

  **-True**

**In MySQL, two different queries that generate the same result table always have the exeustion time.**

  **- False**

**Views can be used to hide rows as well as columns from database users.**

  **-True**

>INSERT INTO AccountView (DepartmentName)

>Values(Music Department)

**-Invalid**

     **The INSERT does not specify a primary key value. Since the base table primary key may not be null, the query is invalid.**

>UPDATE AccountView

>SET DepartmentName = "Information Technology Department'

>WHERE Code = 'Comp';
**-Valid**

   **The UPDATE specifies the primary key, so the base table row is clear.**

>UPDATE AccountView

>SET Difference = 4400

>WHERE Code = 'Comp';

**-Invalid**

    **The UPDATE does not specifiy how the Differance value is allocated to base table columns Budget and Actual.**

>DELETE FROM AccountView

>WHERE DepartmentName = 'History Department'

**-Valid**

   **The WHERE clause clearly indicates which base table row should be deleted.**

- To prevent inserts/updates that appear to fail, databases that support view updates have on optional WITH CHECK OPTION clause. WITH CHECK OPTION is specified, the database rejects inserts & updates that do not statisfy the view query WHERE clause. **The database generates an error message that explains the vioplation instead.**

>CREATE VIEW ViewName [(column1, column2,...)]

>AS Selects Statement

>[WITH CHECK OPTION];

*With check option example*

# 2.9 Lab

Select number of moviews grouped by year.

>SELECT Year, COUNT(Title)

>FROM Movie

>GROUP BY Year;

 # 2.10 Lab

 Select movie ratings with left join.

 >SELECT M.Title, M.Year, R.Description

>FROM Movie AS M

>LEFT JOIN Rating AS R

>ON M.RatingCode = R.Code;

# Section 3
### Section is about MySQL Workbench.

- MySQL is a leading relations database system sponsored by Oracle.

**Refer to the website db.engines.com. What is the overall MySQL ranking compared to all database systems?**

   **-2**

  **^MySQL is the second most popular database system.**

**What account can create other user accounts?**

  **-Root account**

-MYSQL Command-Line Client is a text interface included in the MySQL Server download.

**The root account password is set when installing MySQL.**

  **-True**

**The database server must be manually started each time the user runs the MySQL Command-Line Client.**

  **-False**

**The MySQL Command-Line Client provides a graphical interface for interacting with the database server.**

  **-False**

**MySQL Workbench and MySQL Command-Line Client both allow the user to type SQL statements.**

  **-True**

**The SQL statements in the SQL query panel are not executed unitl the lightening bolt are clicked.**

  **-True.**

**The MySQL Workbench screenshot above shows the columns that makeup the City table.**

  **-True**

- **architecture** describes the components of a computer system and the relationships between components.

- MySQL components are organized in 4 layers:
  - Tools
  - Query Processor
  - Storage Engine (storage management)
  - File System
    
-------

**_Match the parts_**

**Query Processor**

*Manages database connections & compiles SQL queries.*

**Tools**

*Contains MySQL Workbench*

**File System**

*Does not directly interact with the query processor.*

**Storage Engine**

*Executes instructions compiled from SQL queries.*

-------

- **Connection** a link between tools and the query processor.
  
- **Connection Manager** creates connections and manages communications between tools and the query parser.
  
- **Execution plan** is a detailed, *low-level* sequence of steps that specify e3xactly how to process a query.

**Which components detects a missing semicolon at the end of a SQL query?**

  **-Query parser** *Query parser check each SQL statement for correct syntax and converts the statement to an internal representation.*

**Which component detects an incorrect database server address?**

  **Connection Manager** *Proesses connection requests from the tools layer. A connection includes **database name**, **server address**, and **logon credential**.*

**Which component determines that a query was recently executed?**

  **Cache Manager** *The cache is an area of main mermory that contains **recent queries, execution plans, and results, for possible reuse**.*

# Section 4

### Entities, Relationships, and Attributes

*Entity-relationship model* is a high-level representation of data requirements, ignoring implementation details.  

- **Entity** is a person, place, product, concept, or activity.

*A project is an entity*
  
- **Relationship** is a statement about two entities.

*"Task belongs to project" is a relationship.*
  
- **Attribute** is a descriptive property of an entity.

*The duration of a project is an attribute.*
  
- **Reflexive relationship** relates an entity to itself.

- A *Glossary* (data dictionary/repository) document additional detail in text format.

----------------

### Types and Instances

In ER Modeling, a type is a set:

- Entity type is a set of things.
  
  - I.e. All employees in a company.

- Relationship type is a set of related things.
  
  - I.e. Employee-Manages-Department is a set  of (employee, department) pairs, where the employee manages the department.

- Attribute type is a set of values.
  
  - All employee salaries.

An instance is an element of a set:

- Entity instance is an individual thing.
  
  - I.e. The employee Sam Snead.

- Relationship instance is a statement about entity instances.
  
  - I.e. "Maria Rodriguez manages Sales."

- Attribute instance is an individual value.
  
  - I.e. The salary $35k.

--------------

Complex databases are designed in 3 phases:

1. Analysis
2. Logical Design
3. Physical Design

----------------------

Analysis Steps

1. Discover entities, relationships, & attributes
2. Determine cardinatlity
3. Distinguish strong & weak entities
4. Create supertype & subtype entities

------------------------

Logical Deisgn Steps

5. Implement entities
6. Implement relationships
7. Implement attributes
8. Apply normal forms

--------------------

**Analysis considers implementation issues related to a specific database systems.**

  **-False**

**An ER model is developed for all database design projects.**

  **-False**

**Entities, relationships, & attributes always map directly to tables, foriegn keys, & columns, repectively.**

  **-False**

## 4.2 Discovery

**Discovery is a step in which phase?**

  **-Analysis**

**Identification of entities, relationships, & attributes precedes documentation.**

  **-usually**

**Standard attribute types are determined after the ER diagram is drawn.**

  **-usually**

- **Entities** usually appear as **nouns**, but not all nouns are entities.
  
- Designers should ignore nouns that denote specific data or are not relevant to the database.
  
- **Relationships** are often expressed as **verbs**.
  
- Designers should ignore statements that are not about entities, not relevant to the database, or redundant to other relationships.
  
- Designers should look for relationships that are not explicitly stated, since users may over look important information.
  
- **Attributes** are usually **nouns that denote specific data**, such as names, data quantities, and monetary values.

## 4.3 Cardinality

In ER modeling, **cardinality** refers to the maxima & minima of relationships & attributes.

- Relationship *maximum*
  - greatest number of instances 1 entity can related to a single of another instance

Relationship has 2 **maxima**, 1 for each of the related entities.

A related entitiy is singualr when the *maximum is one* and plural when the *maximum is many.*

**On ER diagrams, maxima are shown as 1 or M.**

- Relationship *minimum*
  - least number of instances of one entity that can related to single instance of another entity.

Relationship has 2 **minimum**, one of each of the related entities.

A related entity is *optional* when the minimum is *zero* and *required* when the minimum is  *one*.

**On ER diagrams, minima are shown after maxima in parentheses. I.e. M(1) or M(o)**

![image](https://github.com/user-attachments/assets/11ac6f1b-1d9f-458d-bbaa-27e81e6c0b96)
