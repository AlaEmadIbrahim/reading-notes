# Reading: Bearer Authorization

## Intro to JWT

What is a JSON Web Token (JWT)?

- A JSON Web Token (JWT) is a compact and self-contained way to transmit information between parties as a JSON object. It consists of three parts: a header, a payload, and a signature. The header contains metadata about the token, such as the algorithm used for signing it. The payload contains claims, which are statements about an entity and additional data.
When should we use JSON Web Tokens?

When should we use JSON Web Tokens?

- JSON Web Tokens are commonly used for authentication and authorization purposes in web applications. They provide a secure means of transmitting data between a client and a server. JWTs are especially useful in stateless applications where the server does not need to store session data.

Claims are expected in which structural component of a JWT?

- Claims in a JWT are expected in the payload, which is the second part of the token. The payload contains the actual data or claims about the user or entity being authenticated. These claims can include information like the user's ID, roles, permissions, expiration time, or any other custom data relevant to the application. The claims are represented as key-value pairs within the payload and are encoded as JSON.

## Are JWTs Secure

If I get a JWT and I can decode the payload, how can we call that secure?

- When we say that decoding a JWT payload is secure, it means that the payload integrity and authenticity can be verified. The security of decoding relies on the signature component of the JWT. The signature is created using a secret key known only to the server that issued the token.

If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.

- When sending a JWT, both the sender and receiver must know the secret key used to create the signature. The secret key is appended to the signature component of the JWT. The sender, who creates the token, uses this secret key to sign the token, ensuring its integrity and authenticity. The receiver, who receives the token, needs to possess the same secret key to verify the signature and ensure that the token has not been tampered with during transmission.

Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.

- To explain how concatenated content and a secret can be sent and received securely to a non-technical recruiter, you can use the analogy of a locked box. Imagine the content being the payload and the secret being the key to the box. You can explain that the content payload is combined with the secret key using a specific process signing to create a secure package JWT. When sending the package, it's like sending a locked box. The non-technical recruiter, as the receiver, knows that the box contains important information payload but can't access it without the key secret.

## JWTs Explained

Why use JWT?

- JWT (JSON Web Token) offers several benefits that make it a popular choice for authentication and authorization in web applications. One significant advantage is that it is compact and self-contained, which is useful for various reasons.

JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.

- The self-containment aspect means that all the required information is contained within the JWT itself, just like all the necessary items are neatly packed inside the small box. This eliminates the need for additional storage or reliance on external systems to keep track of session data. The JWT carries all the relevant data it needs, such as user identification, permissions, and expiration time, making it self-sufficient and independent.

What are the three components (the structure) of a JWT signature?

- Header: The header contains metadata about the JWT, such as the algorithm used for signing the token. It typically includes field, both encoded as JSON.

- Payload: The payload carries the actual data or claims about the user or entity being authenticated. It contains the information relevant to the application, such as user ID, roles, permissions, and custom data.

- Signature: The signature is created by taking the encoded header, the encoded payload, and a secret key known only to the server.
