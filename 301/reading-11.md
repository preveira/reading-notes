# Reading-11 #

1. Five differences between SQL and NoSQL

- Data Model
- Scalability
- ACID Compliance
- Data Integrity
- Use Cases

1. **What kind of data is a good fit for an SQL database?**
   - Financial transactions in a banking system. Each transaction can be stored in a table with attributes such as transaction ID, date, amount, and account numbers. Relationships between tables can ensure data integrity and enable complex queries for reporting and analysis.

2. **What kind of data is a good fit for a NoSQL database?**
   - Social media user profiles. Each user profile can be represented as a document with dynamic attributes like name, age, location, interests, and followers. NoSQL databases, like MongoDB, allow flexible schema design, making them ideal for handling diverse and evolving data structures.

3. **Which type of database is best for hierarchical data storage?**
   - Best fit: NoSQL databases, particularly document-based NoSQL databases like MongoDB, are well-suited for storing hierarchical data structures. Documents can contain nested fields, making them suitable for representing hierarchical relationships.

4. **Which type of database is best for scalability?**
   - Best fit: NoSQL databases are typically better suited for scalability due to their ability to scale horizontally across multiple servers. They can handle large volumes of data and high levels of traffic more efficiently than traditional SQL databases.

5. **What does SQL stand for?**
   - Structured Query Language.

6. **What is a relational database?**
   - A relational database is a type of database that stores and retrieves data based on the relationships between data entities. It organizes data into tables with rows and columns, and these tables can be related through primary and foreign key constraints.

7. **What type of structure does a relational database work with?**
   - Relational databases work with a tabular structure where data is organized into tables. Tables consist of rows and columns, and relationships between tables are established using keys.

8. **What is a ‘schema’?**
   - A schema is a formal description of the organization of data within a database, including the structure of tables, data types, constraints, and relationships. It defines the blueprint for how data is stored and accessed.

9. **What is a NoSQL database?**
   - NoSQL (Not Only SQL) databases are a type of database that provides a mechanism for storage and retrieval of data that is modeled in ways other than the tabular relations used in relational databases. They offer flexibility in data models and scalability for modern applications.

10. **How does it work?**
    - NoSQL databases use various data models such as document, key-value, columnar, or graph to store and retrieve data. They typically scale horizontally by distributing data across multiple servers, allowing for efficient handling of large volumes of data and high traffic loads.

11. **What is inside of a MongoDB database?**
    - In MongoDB, data is stored in BSON (Binary JSON) format, which is a binary-encoded serialization of JSON-like documents. Collections contain documents, and each document can have a different structure, providing flexibility in data representation.

12. **Which is more flexible - SQL or MongoDB? and why.**
    - MongoDB is generally considered more flexible than SQL databases because it does not enforce a rigid schema. MongoDB allows for dynamic schema design, meaning documents within a collection can have varying structures, enabling easier adaptation to changing data requirements.

13. **What is the disadvantage of a NoSQL database?**
    - One disadvantage of NoSQL databases is that they often sacrifice some of the features and guarantees provided by traditional SQL databases, such as ACID compliance and strong consistency. Depending on the use case, this trade-off may lead to potential data inconsistency or complexity in application logic to maintain data integrity.

    ## Things I want to know more about ##