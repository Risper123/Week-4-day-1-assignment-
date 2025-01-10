# Week-4-day-1-assignment-
My assignment for week 4 day 1
Assignment Questions
State and Explain the components of a DBMS(Database Management System)


A DBMS is a software system that interacts with end-users, applications, and the database itself to capture and analyze data. Key components include:
 * Data Definition Language (DDL): Used to define the database schema, including creating, altering, and dropping tables, indexes, and views.
 * Data Manipulation Language (DML): Used to manipulate data within the database, such as inserting, updating, deleting, and retrieving data.
 * Data Control Language (DCL): Used to control access to the database, including granting and revoking user privileges.
 * Query Processor: Interprets and executes user queries, optimizing them for efficient data retrieval.
 * Storage Manager: Handles the physical storage of data, including data organization, indexing, and storage allocation.
 * Transaction Manager: Ensures data integrity and consistency during concurrent access and updates.

   

What is a relational database? Give 4 examples.
A relational database organizes data into tables with rows (records) and columns (attributes). Relationships between tables are defined using foreign keys.
 * Examples:
   * MySQL: Popular open-source database used in web applications.
   * PostgreSQL: Powerful open-source database known for its advanced features.
   * Oracle Database: A commercial, enterprise-grade database system.
   * Microsoft SQL Server: A commercial database system from Microsoft.
     

State and Explain three classifications of SQL?
DDL (Data Definition Language):
   * CREATE TABLE: Creates a new table.
   * ALTER TABLE: Modifies an existing table (e.g., add, drop, or modify columns).
   * DROP TABLE: Deletes an existing table.
   * CREATE INDEX: Creates an index to speed up data retrieval.
   * CREATE VIEW: Creates a virtual table based on a query.
 * DML (Data Manipulation Language):
   * SELECT: Retrieves data from the database.
   * INSERT: Adds new rows to a table.
   * UPDATE: Modifies existing data in a table.
   * DELETE: Removes rows from a table.
 * DCL (Data Control Language):
   * GRANT: Grants privileges to users.
   * REVOKE: Revokes privileges from users 

What is the difference between a Primary Key and a Foreign Key?

Primary Key:
   * Uniquely identifies each row in a table.
   * Cannot contain null values.
   * There can only be one primary key per table.
 * Foreign Key:
   * A column in one table that references the primary key of another table.
   * Establishes a relationship between two tables.

What is an Entity-Relationship Diagram?

An ERD is a graphical representation of the entities (tables) and relationships between them in a database. It helps in the design and understanding of the database structure.

What are the advantages of relational databases?
Data Integrity: Ensures data consistency and accuracy.
 * Data Independence: Changes to the physical storage do not affect the logical structure.
 * Flexibility: Easily adaptable to changing requirements.
 * Data Security: Provides mechanisms for controlling access to data.
 * Efficient Data Retrieval: Allows for complex queries and efficient data retrieval.
   

State four types of data type used to store data in tables?
Integer (INT): Stores whole numbers.
 * Character (CHAR/VARCHAR): Stores text data.
 * Date/Time: Stores dates and times.
 * Decimal/Numeric: Stores numbers with decimal places.

What is the purpose of a database management system (DB
Efficient Data Storage and Retrieval: Organizes and stores data in an efficient manner, allowing for quick and easy access.
 * Data Integrity and Consistency: Ensures data accuracy and consistency across the database.
 * Data Security: Provides mechanisms for controlling access to data and preventing unauthorized use.
 * Data Sharing and Concurrency: Allows multiple users to access and modify data concurrently.
 * Data Backup and Recovery: Provides mechanisms for backing up and recovering data in case of failures.
