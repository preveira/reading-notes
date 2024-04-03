# Reading-03 #

1. **Classes are a template for creating ____.**
   
   Classes are a template for creating objects.

2. **Can a class declaration be hoisted?**
   
   No, a class declaration cannot be hoisted. In JavaScript, class declarations are not hoisted like function declarations.

3. **How would you describe a constructor and contextual “this” to a non-technical friend?**
   
   A constructor is like a special function that gets called automatically when you create a new instance of a class. It's used to set up initial values for the object created from the class. The keyword "this" inside a constructor refers to the specific instance of the object being created. So, it's like saying, "this particular object."


4. **Within Express, what does routing refer to?**
   
   Within Express, routing refers to the process of determining how an application responds to a client request to a particular endpoint, or URL.

5. **What is the difference between a route path and a route method?**
   
   The route path is the URL path and can include parameters, whereas the route method is the HTTP method used to access the route, such as GET, POST, PUT, DELETE, etc.

6. **When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?**
   
   It is appropriate to add `next` as a parameter to a route handler when you want to pass control to the next middleware function in the stack. If `next` has been passed to your middleware as a parameter, you must invoke it to pass control to the next middleware function.


7. **What is an Express Router?**
   
   An Express Router is a middleware that allows you to group route handlers for a particular part of your site together and access them using a common route prefix.

8. **By what mean do we initialize express.Router() in an express server?**
   
   We initialize `express.Router()` in an Express server by calling it as a function and assigning it to a variable, like so:
   ```javascript
   const router = express.Router();
   ```

9. **What do we use route middleware for?**
   
   Route middleware is used for tasks such as parsing request bodies, authenticating users, logging, etc. It allows you to modularize your application's functionality and apply specific logic to certain routes or groups of routes.

**What are your learning goals after reading and reviewing the class README?**

I am excited to learn more about Postgres databases and how they work.

## Things I want to know more about ##

