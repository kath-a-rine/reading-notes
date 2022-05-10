# State and Props

As we learn React it is important to understand how methods are used to update components and where in the component lifecycle they fall. State versus props is an important concept to understand how to appropriate pass and update data in React.

## [React Lifecycle](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

Render

2. What is the very first thing to happen in the lifecycle of React?

Mounting is the first phase of the component lifecycle. This is the instance of the component being constructed and inserted to the DOM. The constructor for a component must be called before it is mounted.

3. Put the following things in the order that they happen: constructor, render, React Updates, componentDidMount, componentWillUnmount

4. What does componentDidMount do?

After a component is mounted, this method is invoked. If loading anything with a network request or initializing the DOM, it is best placed in this method.

## [React State vs Props](https://youtu.be/IYvD9oBCuJI)

1. What types of things can you pass in the props?

As props are external to the component, they are used to pass what you want to initialize  your component to or what you want it to render. An example used in the video is a counter. You would use a prop to set the initial count to zero, or to update the state of that component to zero. Props are also useful when setting static information that will not change.

2. What is the big difference between props and state?

Props are outside the component and state is handled inside the component. Props are passed to the component and must be updated outside of the component.

3. When do we re-render our application?

Applications are re-rendered when there is a change or update to their state or props.

4. What are some examples of things that we could store in state?

Using the counter example, you would use state within the component to continually update the count. Another example would be storing user input data from a form.

## Things I want to know more about

I have an okay handle on state versus prop and when it is appropriate to use. I'd like more practice using states and props cement that understanding.
