# Reading-04 #

**What type of database is the best fit for the complex query intensive environment?**

In a complex query-intensive environment, a relational database like SQL is often the best fit. SQL databases are structured in a way that allows for complex querying, joining tables, and performing operations on large datasets efficiently.

**What type of database is the best fit for hierarchical data storage?**

For hierarchical data storage, a NoSQL database is often preferred. NoSQL databases are more flexible and can handle unstructured or semi-structured data well, making them suitable for storing hierarchical data such as JSON or XML documents.

**Describe the differences in scalability between a SQL and NoSQL database as though you were speaking to a non-technical friend.**

Think of SQL databases as like a big, well-organized library where everything has its place. When more people come to the library and want to access books, it might get crowded, and the librarian (the database) has to manage everything very precisely. This makes it harder to scale up quickly because you have to carefully manage each part.

Now, imagine NoSQL databases as a bunch of smaller libraries spread out across the city. Each library can manage its own section independently, and if more people come, you can just open more small libraries. It's easier to scale up because you can add more small libraries without worrying too much about how they all connect.

**Among data tables, what is a one-to-many relationship and how do we “relate” them?**

A one-to-many relationship is like a parent-child relationship. For example, think of a library database. One library can have many books, but each book belongs to only one library. So, the library is the "one" side, and the books are the "many" side. To relate them, you typically use a foreign key in the "many" side table that points back to the primary key in the "one" side table.

**Prior to designing your relational database, it might be useful to ___ a ___ of the database tables and their relationships.**

Prior to designing your relational database, it might be useful to sketch a diagram of the database tables and their relationships. This helps you visualize how the tables are connected and plan out the structure of your database more effectively.

**Explain the difference between a primary and foreign key.**

A primary key is a unique identifier for each record in a table. It ensures that each row in the table is distinct. A foreign key, on the other hand, is a column or set of columns in one table that refers to the primary key in another table. It establishes a link between the two tables, creating a relationship between them.


**How do we treat keywords and parameters differently in SQL syntax?**

In SQL, we use keywords to specify operations like SELECT, INSERT, UPDATE, and DELETE, while parameters are values that we pass to these operations. For example, in a SELECT statement, we might use a WHERE clause with keywords like "AND" or "OR" to filter results based on parameters like a specific value or range of values.

**Define normalization within the context of schemas and data.**

Normalization is the process of organizing data in a database efficiently. It involves breaking down large tables into smaller ones and defining relationships between them. This reduces redundancy and dependency in the data, making it easier to maintain and update.

**Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.**

Sure! Imagine you're organizing a company retreat. In a one-to-one relationship, each employee has exactly one roommate assigned to them. In a one-to-many relationship, one department can have many employees, but each employee belongs to only one department. Finally, in a many-to-many relationship, many employees can attend many events, and vice versa. It's like a big networking event where people can meet multiple people, and multiple people can meet them.

**What are your learning goals after reading and reviewing the class README?**

I am excited to learn more about SQL Associations.

## Things I want to know more about ##
