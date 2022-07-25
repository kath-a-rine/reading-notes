# Context API

## [Context API]()

**What can React Context provide your app?**

A way to pass data through the component tree without having to pass props down manually at every level.

**Why might we use Context?**

Some data may be relevant for many components in an application. That data can be considered "global" for all components(i.e. UI theme, language preferences, location preference, authenticated user). Rather than manually passing that data to every component, context is a way to share that data between components without having to pass props at each level.

**Why should we use it sparingly?**

It makes component reuse more difficult.

## [Other React Context Links]()

**Takeaway 1:** (from ["What's new in React16.3"](https://medium.com/@baphemot/whats-new-in-react-16-3-d2c9b7b6193b))

To access the React Context API use  the `React.createContext()` function. It creates two components: a `Provider` and `Consumer`. The Provider provides data to all components in its sub-tree. The `Consumer` requires access to the same Context component. 

**Takeaway 2:**
[Replacing Redux with core React APIs](https://medium.com/@DidierFranc/replacing-redux-with-the-new-react-context-api-8f5d01a00e8c)