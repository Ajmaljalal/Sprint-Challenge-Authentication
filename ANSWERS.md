<!-- Answers to the Short Answer Essay Questions go here -->

1.  Describe Middleware, Sessions (as we know them in express), bcrypt and JWT.
Middleware: it connects to parts of the application, passes data between them, and if neccessary it wil modify and run some checks on the data as well.

Sessions: are used to check if users are logged in with accurate info, this info is stored in cookies on the local machine.
Bcrypt: It is a password hashing function - a one way hashing.
JWT: It is package -JSON Web Tokens - used for verifying logged if users are logged in to access the protected data.

2.  What does bcrypt do in order to prevent attacks?
It uses  hashing and salting, which produce a random strings, by using specified number of iterations. Thus it makes it harder for the hacker to dcrypt the password.

3.  What are the three parts of the JSON Web Token?
The three parst of JSON Web Token are Header, Payload, and Signature.
