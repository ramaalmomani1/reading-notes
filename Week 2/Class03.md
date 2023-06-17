# Data Modeling

----

**_SQL vs NoSQL:_**

1. What type of database is the best fit for the complex query intensive environment?

> In a complex query intensive environment, a relational databases (RDBMS) or SQL is considered the best fit.

2. What type of database is the best fit for hierarchical data storage?

> For hierarchical data storage NoSQL is the best fit

---

**_SQL modeling techniques_**


1. Among data tables, what is a one-to-many relationship and how do we “relate” them?

> One-to-many relationship allows one entity to be associated with multiple instances of another entity. It is typically established using a foreign key in the "many" entity, referencing the primary key in the "one" entity. This relationship enables data retrieval and manipulation across the entities based on their associated keys.

2. Prior to designing your relational database, it might be useful to ___ a ___ of the database tables and their relationships.

> create a diagrams

3. Explain the difference between a primary and foreign key.

> The primary key uniquely identifies each record in a table. while, a foreign key establishes a link between tables by referencing the primary key of another table, enabling the establishment of relationships between related tables.

----

**_SQL vs NoSQL_**

1. How do we treat keywords and parameters differently in SQL syntax?

>  * Keywords are predefined reserved words in SQL that have specific meanings and roles in SQL statements. They define actions, structures, and conditions like SELECT, INSERT, UPDATE, DELETE... 

> * Parameters are used to represent values that will be provided at runtime. They enhance the flexibility, reusability, and security of SQL statements, typically represented with question marks (?).

2. Define normalization within the context of schemas and data.

>Normalization, in the context of database design, refers to the process of organizing data within a relational database schema to minimize redundancy and dependency issues. It involves breaking down a large table into smaller, more manageable tables 

3. Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.

> * one-to-one: relationship between two tables, each record in one table is associated with at most one record in another table. This relationship is established using primary and foreign keys.

> * one-to-many: relationship between two tables where a single record in one table can be associated with multiple records in another table. This relationship is established using primary and foreign keys.

> *  many-to-many: relationship between two tables where multiple records in one table can be associated with multiple records in another table. This type of relationship requires the use of a junction table, also known as an intermediate or linking table, to establish the association between the two tables.
