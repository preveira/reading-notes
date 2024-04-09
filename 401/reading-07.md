# Reading-7 #

**What is a JSON Web Token (JWT)?**
A JSON Web Token (JWT) is a compact and self-contained method for securely transmitting information between parties as a JSON object. It is commonly used for authentication and authorization in web applications.

**When should we use JSON Web Tokens?**
JSON Web Tokens should be used in scenarios where stateless, compact, and self-contained authentication tokens are needed. They are particularly useful in distributed systems and APIs where scalability and performance are important.

**Claims are expected in which structural component of a JWT?**
Claims are expected in the payload component of a JWT. The payload contains the claims, which are statements about an entity (typically, the user) and additional data.

**If I get a JWT and I can decode the payload, how can we call that secure?**
Decoding the payload of a JWT does not compromise its security because the payload is typically encoded, not encrypted. The security of a JWT lies in its signature, which ensures the integrity of the token. If the signature verification succeeds, it indicates that the token hasn't been tampered with.

**If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.**
When sending a JWT, both the sender and the receiver must know the secret key that is used to generate the signature. This key is appended in the signature component of the JWT.

**Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.**
To send and receive concatenated content and a secret securely to a non-technical recruiter, you can use encryption techniques. Before sending, the content is concatenated with the secret key and then encrypted using a secure encryption algorithm. The encrypted content can be sent over any communication channel. Upon receiving, the recipient can decrypt the content using the shared secret key.

**Why use JWT?**
JWTs are useful because they are compact and self-contained. This means they can be easily transmitted over the network and contain all the necessary information within the token itself, reducing the need for server-side storage and database lookups.

**What are the three components (the structure) of a JWT signature?**
The three components of a JWT signature are the header, the payload, and the signature itself. These components are concatenated with a period ('.') to form the complete JWT.

## Things I want to know more about ##
