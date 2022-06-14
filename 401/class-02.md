# Express, NPM, TDD, CI/CD

## [Express/Node introduction](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction)

***Explain middleware, answer as though I were a non-technical recruiter.***

Middleware is software that functions in between an operating system and the applications on it. It helps build applications efficiently. It is often referred to a "software glue."<sup>1</sup>

***Express the most popular __ __ ____.***

Node web framework.

***Express is “unopinionated.” What does that mean?***

Unopinionated frameworks are not restricted in how to complete tasks, there is no "right way." This flexibility means that in Express "you can insert almost any compatible middleware you like into the request handling chain, in almost any order you like <sup>2</sup>."

***What is a module and why is modularity useful to us as developer?***

Code is split into logical modules, each in their own JS file. Each module has a certain functionality in the code to be called on when needed. A module is a file that can be imported into other code using the Node `require()` function.

As developers, modules are a useful tool in that we don't need to rewrite code. We can instead import it from another file for use elsewhere.

## [What is NPM?](https://docs.npmjs.com/about-npm)

***What version of npm are you running on your machine?***

8.11.0

***What command would you type to install a library/package called ‘jshint’ into your node project?***

`npm i jshint`

## [What is TDD?](https://www.agilealliance.org/glossary/tdd/)

***Explain why tests are important. Please explain as though I were your non technical elder.***

Testing is important to ensuring your code is functioning as it is being built. It reduces the instance of bugs in the code later.

***What are three expected benefits of testing?***

- reduced defects
- reduced effort in final phases of project
- improved design in the code

***Name at lest 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.***

Individual pitfalls: writing too many tests at once, forgetting to run tests frequently, writing tests that are too large

Team pitfalls: partial adoption (only used by some developers), poor maintenance of the test suite, abandoned test suite

## [CI/CD](https://www.youtube.com/watch?v=xSv_m3KhUO8)

***What are three benefits of Continuous Integration?***

- ensure changes integrate
- catch bugs
- reduce merge conflicts

***What is the difference between Continuos Delivery and Continuous Deployment?***

- Continuous Delivery: developing software in a way where it could be released at any time

- Continuous Deployment: deploy new features with little downtime

***Explain how GitHub fits into this process assuming the listener comes from a non-technical background***

GitHub is a "clearing house" for code, allowing developers to make changes locally and push them to GitHub. Uses "webhooks" to send messages to external systems about the activity and events that occur in projects.

### Footnotes

<sup>1</sup> [Wikipedia: Middleware](https://en.wikipedia.org/wiki/Middleware)

<sup>2</sup> [mdn: Express/Node introduction](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction)