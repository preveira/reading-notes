# Reading-13 #

**Which HTTP method would you use to update a record through an API?**

- The HTTP method typically used to update a record through an API is PUT or PATCH.

**Which REST methods require an ID parameter?**

- The REST methods that typically require an ID parameter are PUT, PATCH, and DELETE. These methods are used to update, modify, or delete specific resources identified by their unique IDs.

**What’s the relationship between REST and CRUD?**

- REST (Representational State Transfer) is an architectural style for designing networked applications. CRUD (Create, Read, Update, Delete) is a set of basic operations used to manage resources in a database. The relationship between REST and CRUD is that RESTful APIs often utilize the CRUD operations to perform actions on resources exposed through the API. Each HTTP method in REST corresponds to a CRUD operation: GET (Read), POST (Create), PUT/PATCH (Update), and DELETE (Delete).

**If you had to describe the process of creating a RESTful API in 5 steps, what would they be?**

1. Define the Resources: Identify the entities or objects that your API will expose. Determine the attributes and relationships of these resources.
2. Design the Endpoints: Decide on the URI structure for accessing each resource. Define the HTTP methods (GET, POST, PUT, DELETE) that will be used to perform CRUD operations on these resources.
3. Implement the Server: Develop the server-side application or service that will handle incoming requests to the API endpoints. Use frameworks or libraries suitable for your programming language or platform.
4. Implement Data Persistence: Choose a database system to store and manage the data associated with your resources. Implement the logic to interact with the database, including fetching, creating, updating, and deleting records.
5. Test and Deploy: Test the API endpoints thoroughly to ensure they function correctly and return the expected responses. Once testing is complete, deploy the API to a production environment where it can be accessed by clients over the network.


## Things I want to know more about ##