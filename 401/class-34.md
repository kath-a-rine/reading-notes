# API Integration

## [API Server Build](https://codefellows.github.io/code-401-javascript-guide/curriculum/apps-and-libraries/api-server/)

- **Explain the different between a query string parameter and a path parameter.**

A path parameter defines a location of a resource: `/:id`.
A query string defines what will be filtered within that path like `...products?category=electronics`. Electronics is the query string and products is the path parameter.

- **What would our API URL with a path id parameter be given the following information:**
  - Domain: `http://our-site.com`
  - `v3`
  - model name: `stuff`
  - id: `things`

  `http://our-site.com/v3/stuff/things`

- **We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend.**

The interface can show us the output of various API calls based on the parameters given.

## [Auth Server Build](https://codefellows.github.io/code-401-javascript-guide/curriculum/apps-and-libraries/auth-server/)

**Describe how you would use middleware to implement basic and bearer auth.**

BasicAuth middleware will validate the user on signin. Bearer middleware will run on routes that require a logged in user.

**Describe the handshake necessary to implement OAuth.**

OAuth is used on the /oauth route and handles the handshake process from the 3rd party OAuth system. "*The OAuth processes is initiated in the browser, using a 3rd party authentication/authorization service. It will, once the user has granted permission, invoke a GET on your /oauth route. The OAuth middleware should at this point complete the handshaking process, create/update a local user account in our database, and return an object with a re-authentication/bearer token and the user object.*"

**Describe how Role Based Access Control works to a non-technical friend.**

RBAC means users will only have the capabilities and access allowed to them based on their role within their organization.