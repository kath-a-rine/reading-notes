# React Forms

[React Docs - Forms](https://reactjs.org/docs/forms.html)

1. What is a ‘Controlled Component’?

"An input form element whose value is controlled by React."

2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

Update the state with their responses as they are entered. `handleChange()` runs on every keystroke to update the state, this will display the users input values as they fill out the form.

3. How do we target what the user is entering if we have an event handler on an input field?

By adding a `name` attribute to each `input` element. The handler function will reposond based on the value of `event.target.name`.


[The Conditional (Ternary) Operator Explained}(https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)

1. Why would we use a ternary operator?

Ternary operators condense our code so it is shorter, cleaner, and easier to read.

2. 

```js
x === y ? console.log(true) : console.log(false);
```

## Things I want to know more about

APIs in general. They have been referenced in a few of our readings, but not touched on yet in class.

Reviewing passing props some more.