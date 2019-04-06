1. What is the purpose of using _sessions_?

The purpose of sessions is to store data that you want to access with a request or multiple requests. Which allows your users to have different sessions per user. It allows us to store and access all the user data as the user is connected to our application.

1. What does bcrypt do to help us store passwords in a secure manner.

bcrypt hashes a password so that it is not stored in plain text.  This increases security by minimizing the changes a hacker can grab or decrypt our data

1. What does bcrypt do to slow down attackers?

Bcrypt slows down hackers in a few ways. First, its hashing method is a one way function, so a hacker cannot use Bcrypt in reverse to de-hash sensitive data, even if they have access to the database. Bcrypt also uses salt when hashing sensitive data - which adds random data to the user input to make it even more difficult to de-code. Bcrypt also has a built in parameter to ensure that passwords are of a certain length before being hashed, to provide greater security for the user.

1. What are the three parts of the JSON Web Token?

Header, Payload, Signature