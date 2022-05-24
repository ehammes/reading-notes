# Read: 11 - Mongo and Mongoose

## Reading

### [nosql vs sql](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/)

- **Fill in the chart below with five differences between SQL and NoSQL databases:**
   1. SQL databases are Relational Databases (RDBMS) and NoSQL databases are non-relational or distributed databases
   2. SQL databases have predefined schema whereas NoSQL databases have dynamic schema for unstructured data
   3. *SQL database examples*: MySql, Oracle, Sqlite, Postgres and MS-SQL. *NoSQL database examples*: MongoDB, BigTable, Redis, RavenDb, Cassandra, Hbase, Neo4j and CouchDb
   4. SQL databases are vertically scalable and can manage increasing load by increasing the CPU, RAM, SSD, etc, on a single server. NoSQL databases are horizontally scalable and can add additional servers easily in the NoSQL database infrastructure to handle large traffic.
   5. SQL databases are not best fit for hierarchical data storage. NoSQL database fits better for the hierarchical data storage as it follows the key-value pair way of storing data similar to JSON data. NoSQL database are highly preferred for large data set.
- **What kind of data is a good fit for an SQL database?** Structured data. SQL databases have a predefined schema, used for complex queries, and are best fit for heavy duty transactional type applications
- **Give a real world example.** MySQL database is a popular open-source db that is cost effective, provides a wide range of platforms and languages, and has been around for a long time.
- **What kind of data is a good fit a NoSQL database?** Unstructured data
- **Give a real world example.** MongoDB - most popular NoSQL database. It stores data in JSON like documents and is used by large companies such as The New York Times and Craigslist.
- **Which type of database is best for hierarchical data storage?** NoSQL databases
- **Which type of database is best for scalability?** SQL databases

#### [sql vs. nosql](https://www.youtube.com/watch?v=ZS_kXvOeQ5Y)

- **What does SQL stand for?** Structured query language
- **What is a relational database?** A collection of data items with predefined relationships between them and supports SQL
- **What type of structure does a relational database work with?** A database structure
- **What is a ‘schema’?** All records have to follow a schema that contains a combination of table data (relational)
- **What is a NoSQL database?** Can store lots of collections of data, but documents do not need to use schemas.
- **How does it work?** Data can be fetched and new data can be added. There are no relations, but instead collections of data
- **What is inside of a Mongo database?** MongoDB consists of a database, collections, and documents
- **Which is more flexible - SQL or MongoDB? and why.** MongoDB - can be scaled horizontally and vertically, has great performance for large read and write requests, and is schema-less
- **What is the disadvantage of a NoSQL database?** If write requests effect multiple collections, NoSQL has very few relations

#### Bookmark and Review

- [mongoose api](https://mongoosejs.com/docs/api.html#Model)
- [React Router](https://reactrouter.com/web/api/BrowserRouter)
