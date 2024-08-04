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

### 2.9 Lab

Select number of moviews grouped by year.

>SELECT Year, COUNT(Title)

>FROM Movie

>GROUP BY Year;

 ### 2.10 Lab

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

### Complex databases are designed in 3 phases:

1. Analysis
2. Logical Design
3. Physical Design

----------------------

### Analysis Steps

1. Discover entities, relationships, & attributes
2. Determine cardinatlity
3. Distinguish strong & weak entities
4. Create supertype & subtype entities

------------------------

### Logical Deisgn Steps

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

![image](https://github.com/user-attachments/assets/e499a598-8a3c-48b1-a43e-2cf1deecb9b3)

--------------------------------------

### Discover Entities, Relationhips & attributes

1A. Identify entifies, relationships, and attributes
1B. Draw ER diagram
1C. List standard attribute types in glossary
1D. Document names, synonyms, and descriptions in glossary.

### Determine Cardinality

2A. Determine relationship maxima & minima
2B. Determine attribute maxima & minima
2C. Identify unique attributes
2D. Document Cardinality in glossary &, optionally, on ER diagram

-------------------

## 4.3 

- **Unique attribute** describes at most one entity instance. *A unique attribute is not the same a a singular attribute*
   - Unique attribute has at most one entity instance for each attribute value.
   - Singular attribute has at most one attribute value for each entity instance.

**'Cardinality' refers to relationships only.**

  **-False**

**In ER diagrams, maxima & minima are drawn for relationships only.**

  **-False**

**Maxima & minima usually depend on business rules.**

  **-True**

**In the analysis phase, cardinality is always determined after discovery is complete.**

  **-False**

---------------------------------

## 4.4 Strong and Weak Entities

- **Identifying attribute** is unique, singular, and required.
  
   - Identifying attribute values correspond one to one, or *identify*, entity instances.

- **Strong entity** has one or more identifying attributes.
  
   - When a strong entity is implemented as a table, one of the identifying attributes may become the primary key.

- **Weak entity** does not have an identifying attribute.
  
   - A weak entity usually has a relationship, called an *identifying relationship*, to another entity, called and *identifying entity*. Cardinality of the identifying entity is 1(1).

**In an ER diagram, an identifying relationship has a diamond nex to the identifying entity.**

![image](https://github.com/user-attachments/assets/a06bfb2f-024a-4b6c-a687-e22bcbdd6fac)

*For weak entities, identifying relationships replace identifying attributes.*

--------------------------

### Distinguish strong and weak entitiesa

3A. Identify strong and weak entities.
3B. Determine the identifying relationship(s) for each weak entity.
3C. Document weak entities and identifying relationships in glossary and ER diagram.

--------------------------

*The Project entity has a ProjectCode attribtue.*

**Each project has at most one code. The ProjectCode attribute is ___.**

  **-Singular** *'Singular' means each entity instance has at most one attribute value. This is the case for ProjectCode, so ProjectCode is singular.*

**Each project code describes at most one project.  The ProjectCode attribute is __.**

  **-Unique** *'Unique' means aech attributer value describes at most one entitiy instance. This is the case for ProjectCode, so ProjectCode is unique.*

**A project may have no code. The ProjectCode attribute is ___.**

  **-Optional** *'Optional' means an entitiy instance may have no attribute value.  This is the case for ProjectCode, so ProjectCode is optional.*

**ProjectCode is an identifying attribute of the Project entity.**

  **-False** *An identifying attribute is unique, singular, and required.  ProjectCode is optional, not required, and therefore not an identifying attribute  not an identifying attribute of Project.*

**How often is an identifying entity also a weak entity?**

  **-Sometimes** *An identifying entity may be either weak or strong.*

**How many relationships can identify one weak entity?**

  **-One or many** *A weak entity must have at least one identifying relationship. Some weak entities are identified by several identifying entities.*

**How many weak entities can one entity identify?**

  **Zero, one, or many** *An entity can identify any number of entities, including none.*

**Distinguishing strong and weak entities is a logical design activity.**

  **False** *Distinction between strong and weak entities does not depend on a specific database system.*

**Determining cardinality always precedes distinguishing strong and weak entities.**

  **-False** *Analysis activies are not always done in sequence. Analysis is iterative and, occasionally, steps are done out of order.*

**Database designers may look for identifying relationships first, before noting weak entities.**

  **-True** *Some database designers prefer to focus on identifying relationships rather than weak entities.*

## 4.5 Supertype and subtype entities

- **Subtype entity** is a subset of another entity type, called the **supertype entity**.

**On ER diagrams, subtype entities are drawn within the supertype.**

- A supertype entity usually has several subtypes. Attributes of the supertype apply to all subtypes. Attributes of a subtype do not apply to other subtypes or the supertype.

![image](https://github.com/user-attachments/assets/6ec731ca-f856-4916-83d4-9cf5a575300e)

- Supertype entity identifies its subtype entities.  The identifying relationsihp is called an **IsA relationship**.

- **Similar entities** are entities that have many common attributes and relationships.
  
   - Similar entities become subtypes of a new supertype entity.

- A **Partition** of a supertype entity is a group of mutually exclusive subtype entities.
  
  - A supertype entity can have several partitions.
    
  - Subtype entties within each partition are disjoint and do not shar instances.
    
  - Subtype entties in different partitions overlap and do shar intsances.

**In diagrams, subtype entities within each partition are vertically aligned. Subtype entities in different partitions are horizontally aligned.**

- *Each* partition corresponds to an *optional* **patition attribute** of the supertype entitiy.
  
  - The partition attribute indidcates which subtype entity is associated with each supertype instance.

**An entity instance can be in two subtypes of the same partition.**

  **-False**

**An entity instance can be in two subtypes of different partitions.**

  **-True**

**Each partition attribute value corresponds to one subtype.**

  **-True**

**One partition attribute can correspond to several partitions.**

  **-False**

----------------------------

### Create supertype and subtype entities

4A. Identify supertype and subtype entities.
4B. Replace similar entities and optional attributes with wupertype and subtype entities.
4C. Identify partitions and partitions attributes.
4D. Documents supertypes, subtypes, and partitions in glossary and ER diagram.

----------------------------

Creating supertype and subtype entities is the last of four analysis steps.

  1. Discover entities, relationships, and attributes
  2. Determine cardinality
  3. Distinguish strong and weak entities
  4. Create supertype and subtype entities

---------------------------------

## 4.6 Alternative Modeling Conventions

- **Crow's foot notation** depicts cardinality as a circle(zero), a short line(one), or three short lines (many).
  
   - The three short lines look like a bird's foot.

![image](https://github.com/user-attachments/assets/916d501a-b091-4274-a580-d40dcf82ade5)

- **Subject area** is a group of related entities

- Refer to strong entities as *independent* and weak entities as *dependent*.

-Several model conventions are standardized and widely used. Leading coventions include:

  - **Unified Modeling Language (UML)** is common for software developement
  - **IDEF1X** stands for Information DEFinition version 1X. Became popular partly due to early adoption by the US DDD.
  - **Chen notation** appear in an early ER modeling paper by Peter Chen. Chen notation is not standarized but often appears in literature and tools.

-------------------------------

## 4.7 Implementing Entities

**In the first step of the logical design phase, each *entity* becomes a table and each *attribute* becomes a column.**

- Primary keys must be unique and not NULL, and thus correspond to unique and required attributes.
  
  - Primary keys should also be:
    
    - Stable *Values should not change*
      
    - Simple *Values should be easty to type and store*
      
    - Meaningless *should not contain descriptive information*

- Stable, simple and meaningless primary keys are desirable but not *required.*  Depending on database standards, these guildlines may be violated in some cases.


**A ___ attribute becomes a column that is never NULL.**

  **-required**

**A ___ primary key is easy to specify in a WHERE clause.**

  **-Simple**

**___ columns contain no descriptive information and make good primary keys.**

  **-meaningless**

**A ___ primary key reduces cascading updates in the database.**

  **-stable**

- A strong entity becomes a **strong table.**

- An **artificial key** is a singel-column primary key created by the database designer when no suitable singel-column or composite primary key exists.

**The subtype table primary key is identical to the __ table primary key.**

  **-supertype** *Since subtype entity instances are always supertype entity instances, subtype tables have the same primary key as the supertype table.*

**The primary key of a subtype table is also a ___.**

  **-foreign key** *Since subtype tables are indentified by the supertype table, the primary key of a subtype is a foreign key that references the supertype table.*

**The foreign key in the subtype table usually has the referntial integrity action ___ on primary key delete.**

  **-cascade** *Since a subtype entity instance cannot exist without the corresponding supertype entity instance, delete of a supertype table row should automatically detele the corresponding subtype table row.*

**The foreign key in a subtype table implements the ___ relationship between subtype and supertype entities.**

  **-identifying** *Subtype entities always have a identifying relationship to the supertype, commonly called an 'IsA' relationship.

- A weak entity becomes a **weak table**.

--------------------------

### Implement Entities

5A. Implement strong entities as tables.
5B. Create an artifical key when no suitable primary key exists.
5C. Implement subype entities as tables.
5D. Implement weak entities as tables.
5E. Specify cascade and restric actions for identifying relationships.

-----------------------------

**After the 'implement entities' step is completed, table and column specifications are final.**

  **-False** *The 'implement entities' step is a first pass. Table and column specifications are augmented and revised in subsequent logical designed steps.*

**All design decisions in the 'implement entities' step are affected by the database system.**

  **-False** *Some decisions, such as selection of artificial keys for strong tables, may be affected by the database system.  Other decisions, such as selection of subtype table primary keys, depend on business rules only.*

**Occasionally, database design skips a formal analysis phase and begins with logical design.**

  **-True** *Most databases are complex and benefit from a formal analysis phase. For small databases with just a few users and tables, and ER model might be unnecessary, and database design might begin with table specifications.*

**The activities of the 'implement entities' step are always executed in sequential order.**

  **-False** *All analysis and logical design steps are iterative.  Activities are not usually executed in sequential order.*


## 4.8

- A **many-one *or* one-many** relationship becomes a foeign key:
  - The foreign key goes in the table on the 'many' side of the relationship.
  - The foreign key refers to the primary key on the 'one' side.
  - The foreign key name is the primary key name with an optional prefix.  The prefix is derived from the relationship name and clarifies the meaning of the foreign key.

**Are NULLS allowed in the foeign key column?**

  **-Allowing NULL in the foreign key column depends on relationship minimum.** 

- A **one-one** relationship becomes a foreign key:
  - The foreign key can go in the table on either side of the relationship.  Usually, the foreign key is placed in the table with fewer rows, to minimize the number of NULL  values.
  - The foreign key refers to the primary key on the opposite side of the relationship.
  - The foreighn key name is the primary key name with an optional prefix.  The prefix is derived from the relationship name and clarifies the meaning of the forign key.
 

- A **many-many** relationship becomes a new weak table:
  - The new table contains two foreign keys, referring to the primary keys of the related tables.
  - The primary key of the new table is the composit of the two foreign keys.
  - The new table is identified by the related tables, so primary key cascade and foreign key restrict rules are specified.
  - The new table name consists of the related table names with an optional qualifier in between. The qualifier is derived from the relationship name and clarifies the meaning of the table.

The 'implement relationships' step adds foreign keys to the initial table design.
Foreign keys that implement dependency relationships usually have the following referntial integrity actions:

- Cascade on primary key update and delete
- Restrict on foeign key insert and update

---------------------

### Implement Relationships

6A. Implement many-one relationships as foreign key on 'many' side.
6B. Implement one-one relationships as foreign key in table with fewer rows.
6C. Implement many-many relationships as new weak tables.
6D. Specify cascade and restrict rules on foreign keys that implement dependency relationships.

----------------------------------

**Foreign keys always have the same name as the referenced primary key.**

  **-False** *Foreign key names include the name of the referenced primary key and an optional prefix, derived from the relationship name.*

**Many-one and one-one relationships are always implemented before many-many relationships.**

  **-False** *Relationships can be implemented in any order.*

**The primary key of a table that implements a many-many relationship is composite.**

  **-True** *A many-many relationship becomes a new weak table.  The primary key of the new table is a composite of foreign keys, referring to the related tables.*

4.8.1 Implementing relationships

![image](https://github.com/user-attachments/assets/fb4fd4d2-f41c-4685-b77c-cae541679cd9)


![image](https://github.com/user-attachments/assets/102abf6f-1166-43f1-9a23-cfc9ba068a96)


------------------------------------

## 4.9 Implementing Attributes

In the 'implement entities' step, entities become tables and attributes become columns.  
Singular attributes remain in the initial table, but plural attributes move to a new weak table:

- The new table contains the plural attribute and a foreign key referencing the inital table.

- The primary key of the new table is the composite of the plural attribute and the foreign key.

- The new table is identified by the initial table, so primary key cascade and forign key restrict rules are specified.

- The new table name consisits of the initial table name followed by the attribute name.

If a plural attribute has a *small, fixed maximum*, the plural attribute can be implemented as multiple columns in the initial table.

---------------------------

![image](https://github.com/user-attachments/assets/dcc7b75a-51d4-4529-bb70-ba7c5f3a1eb4)


**What is the name of the new table?**

  **-BookingChangeTimestamp** *The name of the new table containing a plural attribute combines the initial table name and the attribute name.*

**What is the primary key of the new table?**

  **-(FlightNumber, PassengerNumber, ChangedTimestamp)** *All three columns of the new table are necessary for uniqueness and must be included in the compostie primary key of the new table.*

**Which column is a foreign key in the new table?**

  **-(FlightNumber, PassengerNumber)** *(FlightNumber, PassengerNumber) is the primary key of the initial table containing ChangeTimestamp.  When a plural attribute becomes a new dependent table, the primary key of the inital table becomes a foreign key.*

--------------------------------------

**Attribute names always include an attribute type.**

  **-True** *Every attribute name includes the associated attribute type, preceded by an optional entity name and qualifier.*

**Data types are independent of the database system.**

  **-False** *Database systesm support different data types. For this reason, standard data types are specified for attribute types during logical design,m when the database system is considered, rather than during analysis.*

**Data type depends on attribute cardinality.**

  **-False**  *Usually, cardinality is unrelated to data type. Data type of each column can be specified without regard to attribute cardinality.*

----------------

### Implement Attributes

7A. Implement plural attributes as new weak tables.
7B. Specify cascade and restrict rules on new foreign keys in weak tables.
7C. Specify column data types corresponding to attribute types.
7D. Enforce relationship and attribute cardinality with UNIQUE and NOT NULL keywords.

-------------------

**Plural attributes are implemented as new weak tables.**

  **-True**

**The logical design phase ends when attributes have been implemented as columns.**

  **-False** *Following attribute implementation, table are reviewed for third normal form.  Tables that violate third normal form may be revised to eliminate redundant data.*

**An attribute name indicates the data type of the corresponding column.**

  **-True** *Attribute names contain a standard attribute type. Each attribute type corresponds to a data type, documented in the glossary.*


