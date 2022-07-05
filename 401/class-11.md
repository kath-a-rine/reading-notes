# Event Driven Applications

## [Event Driven Programming](https://www.digitalocean.com/community/tutorials/nodejs-event-driven-programming)

*What native Node.js module allows us to get started with Event Driven Programming?*

`EventEmitter`

*What is the value of Object Oriented Programming used in tandem with Event Driven Programming?*

Registering event listeners can be used to alter the flow of communication between objects. Object behavior can be contained within itself rather than accessing external objects. "Rather than and object needing to reach inside another object to trigger a function, objects can emit events and whichever objects are listening to those events will process in the way they are told to." 

*Consider your knowledge of Event Driven Programming in the Web Browser, now explain to a non-technical friend how Event Driven Programming might be useful on the backend using Node.js.*

When you are visiting a webpage, your interactions with that page (ie clicks or scrolls, key pushes) can trigger events on the backend and change what you see or do on the front end. If I am writing an email, clicking "New Email" means the backend now knows what I need on the front end to make that new email message.