# Express REST API

## ES6 Classes

***Classes are a template for creating ____.***

Objects

***Can a class declaration be hoisted?***

Yes, however it's values are not initialized. Functions can be called in code before they are defined, but classes must be defined before they are constructed.

***How would you describe a constructor and contextual “this” to a non-technical friend?***

## Using Express Routing

***Within Express, what does routing refer to?***

How an applications endpoints (URIs) respond to client requests.

***What is the difference between a route path and a route method?***

Route methods are derived from HTTP methods. Route paths define endpoints where requests can be made. 

***When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?***

When there is more than one callback function in your routing method. You would call `next()` within the function to pass control on to the next callback.

## Express Routing

***What is an Express Router?***

A mini express application that only routes.

***By what mean do we initialize express.Router() in an express server?***

By calling `express.Router()`, applying routes to it, and allowing our application to use those routes.

***What do we use route middleware for?***

To do something before a request is processed (checking user authentication, logging data for analytics, anything to be done before information is given to the user).
