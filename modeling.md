# nosql vs sql

What type of database is the best fit for the complex query intensive environment?

- SQL databases are best suited for complex queries.

What type of database is the best fit for hierarchical data storage?

- NoSQL database.

Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend.

- SQL:

  - RELATIONAL DATABASE MANAGEMENT SYSTEM
  - These databases are not suited for hierarchical data storage.
  - These databases are best suited for complex queries.
  - Vertically Scalable.

- NoSQL:

  - Non-relational or distributed database system.
  - These databases are best suited for hierarchical data storage.
  - These databases are not so good for complex queries.
  - Horizontally scalable.

## sql modeling techniques

Among data tables, what is a one-to-many relationship and how do we “relate” them?

- IMAGINE we have 2 tables a,b  a row in table A can have many matching rows in table B. But a row in table B can have only one matching row in table A.

Explain the difference between a primary and foreign key.

- A primary key constraint is a column that uniquely identifies every row in the table of the relational database management system, while a foreign key is a column that creates a relationship between two tables.
- The primary Key never accepts null values, whereas the foreign key may accept multiple null values.
- You can have only a single primary key in a table, while you can have multiple foreign keys in a table.

## sql vs nosql

How do we treat keywords and parameters differently in SQL syntax?

- SELECT >>>> from >>>> where >>>>

Define normalization within the context of schemas and data.

- Is the process of reorganizing data within a database so that users can utilize it for further queries and analysis. Simply put, it is the process of developing clean data.

Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.

- One-to-one: A record in one table is related to one record in another table. One-to-many: A record in one table is related to many records in another table. Many-to-many: Multiple records in one table are related to multiple records in another table.
- example One family lives in one house, and the house contains one family.

### Reflection

What are your learning goals after reading and reviewing the class README?

- relationships between tables and when to use sql Nosql.
