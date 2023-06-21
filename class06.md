# Readings: Authentication

## Securing Passwords

Explain to a non-technical friend how you would safely hash and store a password?

- When we sign up for a website or app, we usually have to choose a password. To make sure our password is safe, the website or app doesn't keep it as it is. Instead, they use something called hashing.

What is Bcrypt?

- Bcrypt is a special way of encrypting passwords. It's purposely made to be slow and require a lot of computing power. This might seem strange, but it's actually a good thing for keeping passwords secure.

Why might you use something like Bcrypt?

- enhances the security of stored passwords.

## Basic Auth

What is Basic Authentication?

- A simple method used to authenticate or verify the identity of a user or client accessing a website or application. It involves sending the username and password in the HTTP request headers to the server for verification.

What properties are necessary in the header of a Basic Auth request?

- Authorization: This property tells the server that Basic Authentication is being used.
= Basic: This keyword indicates the type of authentication being employed, which is Basic Authentication.
= username-password: The username and password are combined, and then encoded using encoding. This encoded value is included in the header as the actual authentication information.

How are username:password in Basic Auth encoded?

- To encode the username and password in Basic Authentication, a process called Base64 encoding is used. Base64 encoding converts binary or text data into a set of ASCII characters that can be safely transmitted over the network.
The username and password are first combined, separated by a colon (":"), to form a string like "username:password". Then, this string is encoded using Base64 encoding. The resulting encoded value is what gets sent in the "Authorization" header of the Basic Authentication request.

## OWASP auth cheatsheet

Define the authentication process to a non-technical recruiter:

- The process of confirming the identity of a user. When someone wants to access a website or an application, they need to prove who they are by providing a username and password.

How should your error messaging respond (both HTTP and HTML)? Why?

- These are the messages sent by the server to the browser when something goes wrong during the authentication process. These messages have three-digit codes, like "404 Not Found", THIS code help both the browser and developers understand what went wrong. For example, a "404 Not Found" error means the requested page or resource doesn't exist.

Bookmark this link also and consider OWASP fundamentals any time you interact with authentication. Applications developed with security in mind from inception have fewer vulnerabilities throughout their lifecycle.

- OWASP fundamentals are important because they emphasize the importance of security when interacting with authentication. OWASP (Open Web Application Security Project) is a community-driven organization that provides resources, guidelines, and best practices for developing secure web applications.

              ____________________________________________________________________________________________


                                         ### [Home Page](./README.md)