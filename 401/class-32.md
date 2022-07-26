# Context API - Behaviors

## [Hooks and Context Example](https://medium.com/swlh/snackbars-in-react-an-exercise-in-hooks-and-context-299b43fd2a2b)

**With regard to the React Context API, what does a “provider” do?**

It is "*responsible for both displaying the local state of the snackbars (we call them alerts), and for exposing an API for globally managing them.*"

**With regard to the React Context API, how would we implement a “consumer” role?**

The custom hook is wraps around the `useContext` React hook.

**Specifically with Context, how are we “wrapping” components to achieve our goals?**

With an opening and closing `Consumer` tag.

## [React Context Links](https://github.com/diegohaz/awesome-react-context)

**Takeaway One:** You can use `toggleTheme` to change the UI theme based on an action.

**Takeaway Two:** You can pass a `store` to a Provider. The `store` holds the same state and actions to update the state.