# Authentication

----

**_Securing Passwords_**

1. Explain to a non-technical friend how you would safely hash and store a password.

> A process called hashing. The computer takes your password and transforms it into a unique code that is stored in a database. When you want to log in, you enter your password, and the computer checks if the code you entered matches the stored code. It adds security to your account,  keep your password safe and helps protect your information

2. What is Bcrypt?

> It's a hashing algorithm designed for securely storing passwords. It helps protect user passwords by making it more challenging for attackers to crack them.

3. Why might you use something like Bcrypt?

>  For password storage because it provides strong security measures. Bcrypt is designed to make it extremely difficult for attackers to guess passwords.

----

**_Basic Auth_**


1. What is Basic Authentication?

> Basic Authentication is a simple method used for user authentication on websites. Users provide their username and password, which are sent with each request to the server. The server verifies the credentials and grants access if they match the stored ones. 

2. What properties are necessary in the header of a Basic Auth request?

> "Authorization" property, which tells the server that authentication information is included. The second property is the encoded "Credentials" consisting of the username and password. The credentials are encoded using Base64, which makes them harder to read. 

3. How are username:password in Basic Auth encoded?

> In Basic Authentication, the username and password are encoded using Base64 encoding. The username and password are combined with a colon in between, like "username:password". This combined string is then transformed into a series of letters, numbers, and symbols using Base64 encoding
----

**_OWASP auth cheatsheet_**

1. Define the authentication process to a non-technical recruiter.

>  Authentication is the process of verifying a user's identity when accessing a system. It involves the user providing their username and password, which are checked against stored records. If the credentials match, the user is granted access; otherwise, access is denied. 

2. How should your error messaging respond (both HTTP and HTML)? Why?

> Error messaging should be handled  in both HTTP responses and HTML pages to provide clear information to users. In HTTP responses, status codes like 404 or 500 indicate the type of error, while reason phrases give a brief description. This helps clients and developers understand the issue. In HTML error pages, user-friendly messages should be displayed. Handling error messaging in both HTTP responses and HTML pages, users can have a better understanding of encountered errors, developers can diagnose issues efficiently, and the overall user experience can be improved.


