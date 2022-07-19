# Component Based UI

## react hello world

*What are the building blocks of a React app?*

Elements and components

*What is the difference between an element and a React component?*

An element "*describes what you see on the screen.*" It is the smallest "building block" of React apps.

A component is like a JavaScript function. It accepts inputs (props) and returns React elements.

*What are some advantages of React’s component based architecture?*

The ability to create complex applications with small reuseable pieces.

## introducing JSX

*What is JSX and why do we use it?*

A syntax extension to JavaScript. It is used "with React to describe what the UI should look like."

*Describe the process of embedding JavaScript expressions in JSX.*

Declare a variable and use it inside JSX by wrapping it in curly brackets.

*Is it safe to embed user input in JSX? Explain.*

Yes. "*By default, React DOM escapes any values embedded in JSX before rendering them. Thus it ensures that you can never inject anything that’s not explicitly written in your application. Everything is converted to a string before being rendered. This helps prevent XSS (cross-site-scripting) attacks.*"

## rendering elements

*Explain what a React Component is to a non-technical friend.*

A component is like a JavaScript function. It accepts inputs (props) and returns React elements.

*Describe mutability and React Components, specifically, how is the UI updated?*

React elements are immutable - meaning it cannot be modified once it is created. The only way to update the UI is to create a new element and pass it to `root.render()`.

*If changes are made to the UI, what does React update?*

React "only updates what's necessary." It will only apply DOM updates needed to "bring the DOM to the desired state."