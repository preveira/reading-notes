# Reading-12 #

**1. In your own words, describe what each group of status code represents:**

100’s = Request has been received and understood, it's not really an error, more like an info message.
200’s = Means that the request from client was received and the server is returning the request.
300’s = Indicates that the client side needs to check on the URL routing for the request.
400’s = Another client side error that indicates issues like syntax, unauthorized access or the resource for the request doesn't exist.
500’s = Error on the server side. (not my monkey's not my problem)

**2. What is a status code 202?**
- **Status code 202:** 
  - **Status:** Accepted
  - This status code indicates that the request has been accepted for processing, but the processing has not been completed yet. It's often used in asynchronous processing scenarios where the server needs more time to fulfill the request. The client should typically check back later for the result.

**3. What is a status code 308?**
- **Status code 308:** 
  - **Status:** Permanent Redirect
  - This status code indicates that the requested resource has been permanently moved to a different URL. It's similar to the more commonly used 301 (Moved Permanently) status code, but it indicates that the redirection should be repeated using the same HTTP method.

**4. What code would you use if an update didn’t return data to a client?**
- If an update didn’t return data to a client, you would typically use **status code 204**.
  - **Status code 204:**
    - **Status:** No Content
    - This status code indicates that the server successfully processed the request but is not returning any content. It's often used in scenarios where the client doesn't need to receive new data in response to an update operation.

**5. What code would you use if a resource used to exist but no longer does?**
- If a resource used to exist but no longer does, you would typically use **status code 410**.
  - **Status code 410:**
    - **Status:** Gone
    - This status code indicates that the requested resource is no longer available at the server and that no forwarding address is known. It's a more explicit version of the 404 (Not Found) status code, indicating that the resource is intentionally gone and not just temporarily unavailable.

**6. What is the ‘Forbidden’ status code?**
- The ‘Forbidden’ status code is **403**.
  - **Status code 403:**
    - **Status:** Forbidden
    - This status code indicates that the server understood the request but refuses to authorize it. It's typically used when the client lacks the necessary permissions to access the requested resource.

Here are the explanations for each of your questions:

**1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?**
   - Storing sensitive information like database credentials directly in code poses security risks, as it could be exposed if the code is shared or version-controlled publicly. By storing such sensitive data in a `.env` file, which is typically not committed to version control, we enhance security by keeping this information private.

**2. What is middleware?**
   - Middleware functions are functions that have access to the request and response objects in an Express application's request-response cycle. They can modify the request and response objects, end the request-response cycle, call the next middleware function in the stack, or perform other tasks. Middleware functions are instrumental in performing tasks such as logging, authentication, authorization, and error handling.

**3. What does `app.use(express.json())` do?**
   - This line of code configures Express to parse incoming requests with JSON payloads. It adds middleware to the Express application that parses incoming request bodies, assuming they are in JSON format, and exposes the resulting object as `req.body` on the request object for further processing.

**4. **What does the `/`:id` mean in a route?**
   - In a route, `/`:id` signifies a route parameter named `id`. This allows the route to match any value provided in the URL segment after the `/` as the `id` parameter. This parameter can then be accessed within the route handler using `req.params.id`.

**5. **What is the difference between PUT and PATCH?**
   - Both PUT and PATCH are HTTP methods used for updating resources. PUT is typically used to update or replace an entire resource, while PATCH is used to apply partial modifications to a resource. In other words, PUT replaces the entire resource with the new data provided, while PATCH updates only the specified fields of the resource, leaving the rest unchanged.

**6. How do you make a default value in a schema?**
   - In Mongoose (for MongoDB schemas), you can specify default values for schema fields using the `default` property when defining the schema. 

**7. What does a 500 error status code mean?**
   - A 500 error status code indicates an internal server error. It means that the server encountered an unexpected condition that prevented it from fulfilling the request made by the client. This error is typically on the server side, and it may require investigation and troubleshooting by the server administrators.

**8. What is the difference between a status 200 and a status 201?**
   - A status code of 200 means "OK" and indicates that the request has succeeded and the server has returned the requested resource. On the other hand, a status code of 201 means "Created" and indicates that the request has been fulfilled and a new resource has been created as a result.


## Things I want to know more about ##