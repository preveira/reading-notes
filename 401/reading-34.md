# Reading-34

### Explain the difference between a query string parameter and a path parameter.

**Query String Parameter:**
- Appears after the question mark (?) in a URL.
- Used to filter, sort, or alter the response from an API without changing the resource.
- Example: `http://example.com/api/stuff?sort=asc&limit=10`

**Path Parameter:**
- Part of the URL path itself and used to identify specific resources.
- Placed within the URL structure.
- Example: `http://example.com/api/stuff/123`

### What would our API URL with a path id parameter be given the following information:

- **Domain:** `http://our-site.com`
- **Version:** `v3`
- **Model name:** `stuff`
- **ID:** `things`

**API URL:**
```
http://our-site.com/v3/stuff/things
```

### We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend.

Imagine our API is like a waiter at a restaurant. When you go to a restaurant, you tell the waiter what you want, and they bring it to you. Similarly, the API interface takes requests from users, figures out what data or actions they need, and brings back the right information or performs the requested action.

### Describe how you would use middleware to implement basic and bearer auth.

**Basic Authentication:**
1. Intercept incoming requests.
2. Check for the `Authorization` header.
3. Decode the header to extract the username and password.
4. Validate these credentials against your user database.
5. Allow the request to proceed if valid; otherwise, respond with an error.

**Bearer Authentication:**
1. Check for a bearer token in the `Authorization` header.
2. Extract and verify the token.
3. Validate the token against your authentication service.
4. Allow the request to proceed if valid; otherwise, respond with an error.

### Describe the handshake necessary to implement OAuth.

1. **Client Registration:**
   - Register your app with the OAuth provider to get a client ID and secret.

2. **Authorization Request:**
   - Redirect the user to the OAuth provider’s authorization server.

3. **User Authorization:**
   - User logs in and grants permission to your app.

4. **Authorization Code:**
   - OAuth provider redirects back with an authorization code.

5. **Token Exchange:**
   - Exchange the code for an access token using the client ID and secret.

6. **Access Token:**
   - Receive an access token to make authenticated requests.

### Describe how Role Based Access Control works to a non-technical friend.

Think of Role Based Access Control (RBAC) like a hotel key system. Each person gets a key card that lets them into certain rooms based on their role.

- **Guest:** Can access their own room and common areas.
- **Housekeeping:** Can access all guest rooms for cleaning.
- **Manager:** Can access all areas.

In software, users have roles with specific permissions, ensuring they can only access what they're supposed to. This keeps everything secure and organized.

## Things I want to know more about
