# Read: 04 - Data Modeling

## Reading

[nosql vs. sql](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool)

1. **What type of database is the best fit for the complex query intensive environment?** SQL databases
2. **What type of database is the best fit for hierarchical data storage?** NoSQL databases
3. **Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend.** SQL databases are vertically scalable, meaning you can increase the load by increasing the CPU, RAM, SSD, etc, on a single server. NoSQL databases are horizontally scalable by adding additional servers to the infrastructure to handle large traffic.

[sql modeling techniques](https://www.essentialsql.com/get-ready-to-learn-sql-7-simplified-data-modeling/)

1. **Among data tables, what is a one-to-many relationship and how do we “relate” them?** A one-to-many relationship means an entry in one table is related to more than one entry in another table and are related using keys.
2. **Prior to designing your relational database, it might be useful to ___ a ___ of the database tables and their relationships.** Create a diagram
3. **Explain the difference between a primary and foreign key.** Primary keys uniquely identify each row in a table and can have multiple primary keys (which is called a compound key). A foreign key is a column or set of columns that match a primary key in another table.

### Videos

[sql vs nosql](https://www.youtube.com/watch?v=ZS_kXvOeQ5Y)

1. **How do we treat keywords and parameters differently in SQL syntax?** Keywords are reserved words in SQL, are used to perform operations in the database, and can be written in upper or lower case letters. Parameters are used to exchange data.
2. **Define normalization within the context of schemas and data.** Bringing in data must adhere to the schema and be in a format that fits the table
3. **Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.** A one-to-one relationship means a record in a table is related to one record in another table. A one-to-many relationship occurs when a record in one table is related to multiple records in another table. A many-to-many relationship is when multiple records in a table are associated with multiple data records in another table.

### Bookmark and Review

[sequelize api](https://sequelize.org/master/)