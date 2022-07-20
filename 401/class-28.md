# Component Lifecycle/`useEffect` Hook

## effects hook

*What purpose does `useEffect` serve in a function component compared to its counterpart(s) in class components?*

In class components, side effects are put into `componentDidMount` and `componentDidUpdate`. With  `useEffect` in functional components, we no longer need to duplicate code in those two methods.

*When using the `useEffect` Hook:*

- *What does `useEffect` do?*

`useEffect` performs side effects in function components. It tells React your component must do something after render. The function is remembered and is called after performing DOM updates. By default it runs after the first render and after every update.

- *Why is `useEffect` called inside a component?*

It is called inside a component so it can access any state variables or props from the effect.

*Explain the importance of properly implementing effects with Cleanup*

Some effects will require cleanup, like a subscription to an outside data source. Cleanup is important so we do not introduce a "memory leak." It also helps avoid bugs. 