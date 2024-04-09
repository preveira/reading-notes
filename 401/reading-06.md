# reading-06 #

**Explain to a non-technical friend how you would safely hash and store a password.**

To safely hash and store a password, we use a special mathematical function called a hash function. Think of it like a secret recipe that takes your password and mixes it up in a way that it can't be unscrambled. This scrambled version of your password is what we store in our database. So, whenever you log in, we just take the password you entered, scramble it the same way, and check if it matches the scrambled version we have stored. This way, even if someone gets access to our database, they can't see your actual password because it's all scrambled up!

**What is Bcrypt?**

Bcrypt is a type of cryptographic hashing function specifically designed for securely storing passwords. It's widely used because it's very difficult for attackers to reverse-engineer passwords from the hashes it generates.

**Why might you use something like Bcrypt?**

We use Bcrypt or similar hashing functions because they add an extra layer of security to our users' passwords. Bcrypt makes it extremely difficult for hackers to figure out the original passwords, even if they somehow get access to our database. This helps protect our users' accounts from being compromised.

**What is Basic Authentication?**

Basic Authentication is a simple method for securing web pages or APIs by requiring a username and password to access them.

**What properties are necessary in the header of a Basic Auth request?**

In a Basic Auth request, the header must include the word "Basic" followed by a space and then the Base64-encoded string of the username and password combined with a colon separator.

**How are username:password in Basic Auth encoded?**

The username and password in Basic Auth are encoded using Base64 encoding, which is a way of representing binary data in an ASCII string format. This encoded string is then included in the header of the request.

**Define the authentication process to a non-technical recruiter.**

The authentication process is like the security checkpoint at the entrance of a building. When you want to enter, you need to show your ID (username) and a passcode (password). The security guard checks if they match what's on their list. If they do, you're allowed in; if not, you're denied access.

**How should your error messaging respond (both HTTP and HTML)? Why?**

Error messages should be clear and helpful, both in the HTTP response headers and in the HTML content. This helps users understand what went wrong and how to fix it. It also prevents potential attackers from guessing usernames or passwords by providing vague error messages.

## Things I want to know more about ##
