# Reading-15 #

What is OAuth?

OAuth (Open Authorization) is an open standard for authorization that enables third-party services to access a user's resources without needing to expose their credentials. It is commonly used to allow users to grant third-party applications limited access to their resources without sharing their passwords.

Give an example of what using OAuth would look like.

1. A user wants to log in to a website using their Google account.
2. The website redirects the user to Google's authentication server.
3. The user enters their Google username and password.
4. Google prompts the user to grant permission to the website to access certain information (e.g., profile information, email address).
5. If the user agrees, Google provides the website with an access token.
6. The website can then use this access token to make authorized requests on behalf of the user to Google's APIs.

How does OAuth work? What are the steps that it takes to authenticate the user?

1. **Authorization Request:** The client (third-party application) requests authorization from the resource owner (user) to access their resources.
2. **Authorization Grant:** The resource owner authorizes the client's request.
3. **Token Request:** The client requests an access token from the authorization server using the authorization grant.
4. **Token Response:** The authorization server verifies the authorization grant and issues an access token to the client.
5. **Accessing Protected Resources:** The client presents the access token to the resource server to access the protected resources.

What is OpenID?

OpenID is an authentication protocol that allows users to use a single set of credentials (such as a username and password) to access multiple websites or services without needing to create separate accounts for each. It enables Single Sign-On (SSO) across different domains.

What is the difference between authorization and authentication?

The difference between authorization and authentication is that authentication is the process of verifying the identity of a user, typically by validating credentials like a username and password, whereas authorization is the process of determining what actions a user is allowed to perform after they have been authenticated.

What is Authorization Code Flow?

Authorization Code Flow is an OAuth 2.0 flow where the client first obtains an authorization code from the authorization server, then exchanges it for an access token. This flow is commonly used for server-side applications.

What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

Authorization Code Flow with Proof Key for Code Exchange (PKCE) is an enhanced version of the Authorization Code Flow that provides additional security by preventing interception of the authorization code.

What is Implicit Flow with Form Post?

Implicit Flow with Form Post is an OAuth 2.0 flow primarily designed for browser-based applications where the access token is returned directly in the URL fragment.

What is Client Credentials Flow?

Client Credentials Flow is an OAuth 2.0 flow used by clients to obtain an access token by directly authenticating with the authorization server using their client credentials.

What is Device Authorization Flow?

Device Authorization Flow is an OAuth 2.0 flow designed for devices with limited input capabilities where the user authorizes the device through a secondary device or web browser.

What is Resource Owner Password Flow?

Resource Owner Password Flow is an OAuth 2.0 flow where the client directly obtains the resource owner's username and password and uses them to obtain an access token. This flow should only be used when other flows are not feasible.

## Things I want to know more about ##