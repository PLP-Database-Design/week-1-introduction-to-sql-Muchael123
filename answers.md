# Assignment Answers

## 1. State and Explain the components of a DBMS (Database Management System)
A DBMS is software that facilitates the creation, management, and use of databases. The key components of a DBMS are:

- **Database Engine**: Responsible for storing, retrieving, and managing data in the database. It ensures efficient query processing and transaction management.
- **Data Definition Language (DDL)**: Enables users to define the structure of the database, such as creating, altering, or deleting tables.
- **Data Manipulation Language (DML)**: Used for querying and modifying data within the database. Includes operations like SELECT, INSERT, UPDATE, and DELETE.
- **Database Schema**: Defines the logical structure of the database, such as tables, relationships, and constraints.
- **Query Processor**: Interprets and executes database queries written in SQL.
- **Transaction Manager**: Ensures the ACID (Atomicity, Consistency, Isolation, Durability) properties of database transactions.
- **Data Security and Integrity**: Protects data from unauthorized access and ensures the accuracy and consistency of the data.
- **Concurrency Control**: Manages simultaneous access to the database by multiple users to prevent conflicts.

---

## 2. What is a relational database? Give 4 examples.
A relational database is a type of database that organizes data into tables (relations) consisting of rows (records) and columns (fields). Data is stored in a structured format, and relationships between tables are defined using keys.

### Examples:
1. MySQL
2. PostgreSQL
3. Oracle Database
4. Microsoft SQL Server

---

## 3. State and Explain three classifications of SQL
SQL is classified into several types based on its functionalities:

1. **Data Definition Language (DDL)**:
   - Used to define or modify the structure of the database.
   - Commands include `CREATE`, `ALTER`, `DROP`, `TRUNCATE`.
   - Example: `CREATE TABLE users (id INT, name VARCHAR(50));`

2. **Data Manipulation Language (DML)**:
   - Used to manipulate data in the database.
   - Commands include `SELECT`, `INSERT`, `UPDATE`, `DELETE`.
   - Example: `INSERT INTO users (id, name) VALUES (1, 'John Doe');`

3. **Data Control Language (DCL)**:
   - Used to control access to the database.
   - Commands include `GRANT`, `REVOKE`.
   - Example: `GRANT SELECT ON users TO public;`

---

## 4. What is the difference between a Primary Key and a Foreign Key?
- **Primary Key**: A unique identifier for each record in a table. It must contain unique values and cannot be NULL.
  - Example: `id` in a `users` table.
- **Foreign Key**: A field in one table that references the Primary Key in another table, establishing a relationship between the two tables.
  - Example: `user_id` in an `orders` table referencing `id` in the `users` table.

---

## 5. What is an Entity-Relationship Diagram?
An Entity-Relationship Diagram (ERD) is a visual representation of entities (objects or concepts) within a system and their relationships. It is commonly used in database design to map out the logical structure of the database, including tables, attributes, and connections.

### Example:
- Entities: Users, Orders
- Relationships: Users place Orders (one-to-many relationship).

---

## 6. What are the advantages of relational databases?
1. **Data Integrity**: Ensures data accuracy and consistency through constraints and rules.
2. **Flexibility**: Supports complex queries and relationships between data.
3. **Scalability**: Can handle large amounts of data efficiently.
4. **Security**: Provides access control mechanisms to secure data.
5. **Standardized Query Language**: SQL is widely used and understood across systems.

---

## 7. State four types of data types used to store data in tables.
1. **Integer**: Stores whole numbers.
   - Example: `INT`, `SMALLINT`, `BIGINT`.
2. **Character/String**: Stores text data.
   - Example: `CHAR`, `VARCHAR`, `TEXT`.
3. **Date/Time**: Stores date and time information.
   - Example: `DATE`, `TIME`, `DATETIME`, `TIMESTAMP`.
4. **Floating Point/Decimal**: Stores numbers with decimal points.
   - Example: `FLOAT`, `DOUBLE`, `DECIMAL`.

---

## 8. What is the purpose of a database management system (DBMS)?
The purpose of a DBMS is to provide an interface for users to interact with databases efficiently and securely. It helps in:
1. **Data Storage and Retrieval**: Manages the storage of large amounts of data and enables quick retrieval.
2. **Data Security**: Protects data from unauthorized access.
3. **Data Integrity**: Maintains data accuracy and consistency.
4. **Concurrent Access**: Allows multiple users to interact with the database simultaneously without conflicts.
5. **Ease of Management**: Simplifies the creation, maintenance, and administration of databases.

---
