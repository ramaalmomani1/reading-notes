# Bearer Authorization

----

**_Intro to JWT_**

1. What is a JSON Web Token (JWT)?

> A JSON Web Token (JWT) is a compact and secure way of transmitting information between parties as a JSON object. It consists of a header, payload, and signature. JWTs are used for authentication and authorization purposes in web applications and APIs. 


2. When should we use JSON Web Tokens?

> Used where secure authentication and authorization are required. Examples: web applications, mobile applications and APIs

3. Claims are expected in which structural component of a JWT?


>  Payload component of JWT

----

**_Are JWTs Secure?_**


1. If I get a JWT and I can decode the payload, how can we call that secure?


> The security of JWTs relies heavily on digital signature verification, which ensures the integrity and authenticity of the token. In addition, the use of secure transmission protocols such as HTTPS prevents the JWT from being intercepted and tampered with in transit. Implementing these security measures can significantly reduce the risk of unauthorized access  of JWTs.

2. If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.


> Both must know the secret key that is used for generating and verifying the token's signature. The secret key is appended to the signature part of the JWT

3. Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.

> The content and secret key should be shared through a secure channel. The recruiter should be instructed to store the secret key in a secure location, preferably offline and it's important to emphasize the need to keep the secret key confidential and not share it with anyone else. 

----

**_JWTs Explained_**

1. Why use JWT?


> JWTs provide a secure way for authentication, authorization, and secure information exchange, making them a preferred choice in web and application development.

2. JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.

>  It is a small and self-sufficient package of information, it simplifies the process of transmitting and handling data securely. With JWT, there is no need to rely on external storage or complicated setups.

3. What are the three components (the structure) of a JWT signature?

> * Header -> contains information about the token
> * Payload -> contains the actual data being transmitted within the token
> * Secret Key 
