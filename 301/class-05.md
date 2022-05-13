# Putting it all together

## [React Docs - Thinking in React](https://reactjs.org/docs/thinking-in-react.html)

1. What is the `single responsibility principle` and how does it apply to components?

The single responsibility principle is a technique for identifying what needs to be its own function or object. The principle states that a component should have a single responsibility, do only one thing. If a component ends up needing to do many things, it should be broken down into subcomponents.

2. What does it mean to build a ‘static’ version of your application.

Once you’ve determined the hierarchy it is time to build a static version of your application. Building a static version of your applications means you are building the model and rendering the UI, but there is no interactivity. When building a static version, you should only use props (passing data from parent to child).

3. Once you have a static application, what do you need to add?

Identify the minimal set of state that your app will need to work.

4. What are the three questions you can ask to determine if something is state?

* Is it passed in from a parent via props? If so, it probably isn’t state.
* Does it remain unchanged over time? If so, it probably isn’t state.
* Can you compute it based or any other state o props in your component? If so, it probably isn’t state.

5. How can you identify where state needs to live?

Identify every component that renders something based on state and find the common owner component. The common owner component or another higher up component should own the state.

## [Higher-Order Functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)

1. What is a “higher-order function”?

A function that operates on other functions either by taking them as arguments or returning them.

2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

Line 2 is returning a boolean: if the value of m is greater than the parameter value of the greaterThan function then it returns true. 

3. Explain how either map or reduce operates, with regards to higher-order functions.

The map method will apply a function to all the elements of an array and return a new array of those new values. The reduce method repeatedly takes a single value from an array and combines it with the current value. It takes in an array, a combine function, and a start value.

## Things I want to know more about

Inverse data flow.
I’d like more practice building with React and using the single responsibility principle.
