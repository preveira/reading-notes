# Reading-08 #

Here are the answers to your questions about API design best practices:

1. **What does REST stand for?**
   - REST stands for Representational State Transfer.

2. **REST APIs are designed around a ____?**
   - REST APIs are designed around a stateless client-server architecture.

3. **What is an identifier of a resource? Give an example.**
   - An identifier of a resource is a URI (Uniform Resource Identifier). Example: `/users/123`.

4. **What are the most common HTTP verbs?**
   - The most common HTTP verbs are GET, POST, PUT, PATCH, and DELETE.

5. **What should the URIs be based on?**
   - URIs should be based on nouns representing resources, not verbs.

6. **Give an example of a good URI.**
   - Example: `/products/123`.

7. **What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?**
   - A 'chatty' web API is one that requires multiple requests to accomplish a single task due to fine-grained resources. It's generally considered a bad thing because it can lead to increased network overhead and reduced performance.

8. **What status code does a successful GET request return?**
   - A successful GET request returns status code 200 (OK).

9. **What status code does an unsuccessful GET request return?**
   - An unsuccessful GET request returns status code 404 (Not Found) if the resource is not found, or 400 (Bad Request) if the request is malformed.

10. **What status code does a successful POST request return?**
    - A successful POST request returns status code 201 (Created) if a new resource is created.

11. **What status code does a successful DELETE request return?**
    - A successful DELETE request returns status code 204 (No Content).

## Things I want to know more about ##