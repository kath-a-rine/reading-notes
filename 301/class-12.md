# CRUD

## [Status Codes Based on REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)

1. *In your own words, describe what each group of status code represents:*

* 100’s = informational
* 200’s = success
* 300’s = redirection
* 400’s = client error
* 500’s = server error

2. *What is a status code 202?* - accepted. Tells the client their request was valid and accepted and will finish processing in the future.
3. *What is a status code 308?* - permanent redirect. Redirects the client to a different URL to access a resource, as the old one was invalid.
4. *What code would you use if an update didn’t return data to a client?* - 204 No content
5. *What code would you use if a resource used to exist but no longer does?* - 410 Gone
6. *What is the ‘Forbidden’ status code?* - 403, the client is not permitted to access the resource.

## [Build a REST API with Node.js, Express, and MongoDB](https://youtu.be/fgTGADljAeg)

1. *Why do we need to pull our MongoDB database string out of our server and put it into our .env?* - Because it contains our your individual database credential, so we want it in the env file where sensitive information is not pushed to GitHub.
2. *What is middleware?* - Code that runs when a server gets a request, but before it is passed to the routes.
3. *What does app.use(express.json()) do?* - Allows the server to accept json as a body.
4. *What does the /:id mean in a route?* - It is a parameter that allows access to anything passed in after `/`.
5. *What is the difference between PUT and PATCH?* - PATCH will update specified data, whereas PUT will update all data.
6. *How do you make a default value in a schema?* - set a default key within the schema with a default value.
7. *What does a 500 error status code mean?* - There is an error on the server, having nothing to do with user input.
8. *What is the difference between a status 200 and a status 201?* - 200 is a general "sucessful" status whereas 201 is more specific. It means the creation of something, in this case an object, was successful.
