# Authentication

## [Securing Passwords](https://thehackernews.com/2014/04/securing-passwords-with-bcrypt-hashing.html)

***Explain to a non-technical friend how you would safely hash and store a password.***

***What is Bcrypt?***

*"Bcrypt is an adaptive hash function based on the Blowfish symmetric block cipher cryptographic algorithm and introduces a work factor (also known as security factor), which allows you to determine how expensive the hash function will be."*  The BCrypt algorithm uses the *key stretching* technique.

***Why might you use something like Bcrypt?***

BCyrpt can slow a brute force attack.

## [Basic Authentication](https://en.wikipedia.org/wiki/Basic_access_authentication)

***What is Basic Authentication?***

A method for a web browser to provide a username and password.

***What properties are necessary in the header of a Basic Auth request?***

The header field is in this format: `Authorization: Basic <credentials>`. The credentials are the Base64 encoding of an ID and password joined by a colon `:`.

***How are username:password in Basic Auth encoded?***

With [Base64](https://en.wikipedia.org/wiki/Base64) encoding. It is "a group of binary-to-text encoding schemes that represent binary data."

## [OWASP auth cheatsheet](https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html)

***Define the authentication process to a non-technical recruiter.***

Authentication is the process of verifying that an individual, website, or other entity is who they claim to be. This done by the submission of a username or ID and some private information that only a given user would know (like a password).

***How should your error messaging respond (both HTTP and HTML)? Why?***

The error message should be generic and applicable in many cases. Saying "The User ID or password was incorrect" is better than specifying which one was incorrect.