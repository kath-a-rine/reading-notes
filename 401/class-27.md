# `useState()` Hook

## Introducing Hooks

*What was the motivation for introducing Hooks?*

To solve a variety of problems in React.

*What changes are important regarding implementing Hooks versus Component Classes?*

- "Hooks allow you to reuse stateful logic without changing component hierarchy"
- "Hooks let you split one component into smaller functions based on what pieces are related"
- "Hooks let you use more of React's features without classes"

*Hooks allow you to reuse stateful logic without changing ___ _______.*

component hierarchy

## hooks api

*Name two rules imposed by React Hook usage.*

- Only call Hooks at the top level. Don’t call Hooks inside loops, conditions, or nested functions.
- Only call Hooks from React function components. Don’t call Hooks from regular JavaScript functions.

*How would you identify a custom Hook and why might you create one?*

It is a custom Hook if the function name starts with `use` and calls other Hooks. Custom Hooks can cover many use cases to fit your needs.

## the state hook

*What is a Hook?*

A special function that lets you "hook into" React features.

*When would I use the `useState` Hook?*

When you want to add React state to a function component.

*If you were to add React state to a function component by declaring a state variable:*

- *What does calling `useState` do?*

Declares a "state variable."

- *What do we pass to `useState` as an argument?*

The initial state.

- *What does `useState` return?*

A pair of values: the current state and a function that updates it.