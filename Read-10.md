## Database Schema
A Database Schema is a visual representation or blueprint of the structure of a database. It defines the organization, relationships, and constraints of the data stored in the database. A schema includes tables, columns, data types, constraints, and relationships between tables.
1. What is a Schema?
   A schema is a logical container that represents the structure and organization of a database. It defines the tables, columns, relationships, constraints, and other elements within a database.
2. Why do we use them?
   Database schemas provide a standardized way to define and manage the structure of a database. They ensure data integrity, facilitate data organization and querying, and provide a basis for collaboration among developers, administrators, and users working with the database.
3. What do they look like?
   Schemas can be represented visually using diagrams or schematics that show the tables, columns, and relationships. They can also be described using Data Definition Language (DDL) statements in database management systems such as SQL.
4. What are the different types of Database Keys?
   In database design, different types of keys are used to establish relationships and ensure data integrity. Some common types of keys include:
   - Primary Key: A primary key uniquely identifies each record in a table.
   - Foreign Key: A foreign key establishes a link between two tables by referencing the primary key of another table.
   - Composite Key: A composite key consists of two or more columns that together form a unique identifier for a record.
   - Candidate Key: A candidate key is a column or combination of columns that could potentially serve as the primary key.
   - Surrogate Key: A surrogate key is an artificially generated key, often an auto-incremented number, used as the primary key.
5. What is a Primary Key?
   A primary key is a column or combination of columns that uniquely identifies each record in a table. It enforces entity integrity, meaning it ensures that each record has a unique identifier. Primary keys are used to establish relationships with other tables through foreign keys.
6. What is a Foreign Key?
   A foreign key is a column or combination of columns in one table that refers to the primary key of another table. It establishes a relationship between two tables, enforcing referential integrity. Foreign keys ensure that data in the referencing table (child table) corresponds to the data in the referenced table (parent table).
7. What is a Composite Key?
   A composite key is a key that consists of two or more columns that, when combined, form a unique identifier for a record. The combination of these columns must be unique within the table. Composite keys are used when a single column cannot uniquely identify a record.
8. How are they different? When do you use one over the others?
   - Primary keys are used to uniquely identify records within a table and are crucial for data integrity. Each table should have a primary key.
   - Foreign keys are used to establish relationships between tables. They reference the primary key of another table to ensure data consistency and enforce referential integrity.
   - Composite keys are used when a single column cannot uniquely identify a record. They consist of multiple columns that, when combined, form a unique identifier.
   - Candidate keys are columns or combinations of columns that can potentially serve as the primary key. They are alternative choices for primary keys.
   - Surrogate keys are artificially generated keys used as primary keys, typically for performance or simplicity reasons.
   

In a relational database, relationships define how tables are connected or associated with each other based on their data. There are different types of relationships that can exist between tables:
1. One-to-One (1:1) Relationship:
   In a one-to-one relationship, one record in a table is associated with only one record in another table, and vice versa. It means that for each record in Table A, there is only one matching record in Table B, and vice versa. This relationship is typically represented by having a foreign key column in one table referencing the primary key column of the other table.

2. Many-to-Many (M:M) Relationship:
   In a many-to-many relationship, multiple records in one table can be associated with multiple records in another table, and vice versa. This type of relationship requires the use of a junction table or an intermediate table to establish the connections between the two tables. The junction table holds the foreign keys of both tables, forming the relationships.

3. One-to-Many (1:M) Relationship:
   In a one-to-many relationship, a record in one table can be associated with multiple records in another table, but each record in the other table is associated with only one record in the first table. This relationship is commonly represented by having a foreign key column in the "many" table that references the primary key column of the "one" table.

4. Many-to-One (M:1) Relationship:
   The many-to-one relationship is the reverse of the one-to-many relationship. In this case, multiple records in one table can be associated with a single record in another table. This is typically represented by having a foreign key column in the "many" table that references the primary key column of the "one" table.

These relationship types allow for organizing and structuring data across multiple tables in a relational database, enabling efficient querying, data integrity, and data management. By establishing relationships between tables, related information can be linked together and retrieved as needed based on the specified relationships.
