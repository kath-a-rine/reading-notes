# Bearer Authorization

## Intro to JWT

*What is a JSON Web Token (JWT)?*

An open standard, self-contained method used to securely transfer information between two parties.

*When should we use JSON Web Tokens?*

For authorization and information exchange.

*Claims are expected in which structural component of a JWT?*

the Payload

## Are JWTs Secure?

*If I get a JWT and I can decode the payload, how can we call that secure?*

Without knowing the private key, you cannot alter the data.

*If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.*

The payload and the secret.

*Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.*

The signature holds the concatenated content and secret. If the recipient does not know what key was used, they won't be able to calculate the signature.

## JWTs Explained

*Why use JWT?*

Because it is digitally signed meaning the information being sent id already verified and trusted. The data has not been changed during the transfer.

*JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.*

JWT can be sent via URL, POST request or HTTP Header.Compact means it can transfer data quickly. Self-contained means it contains information about the user. You can avoid sending many search requests to the database since it already holds all the user information.

*What are the three components (the structure) of a JWT signature?*

- The header - a JSON object containing two fields: algorithm (alg) and type (typ)
- the payload - a JSON object containing claims (user details or additional metadata)
- the signature - holds the base64 header and base64 payload with secret
