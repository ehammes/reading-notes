# Read: 31 -  Context API

## Reading

[Context API](https://reactjs.org/docs/context.html)

1. **What can React Context provide your app?** Context provides a way to share data between components without having to explicitly pass a prop through every level of the tree.
2. **Why might we use Context?** Designed to share data that is considered global and can avoid passing props through intermediate elements
3. **Why should we use it sparingly?** Context is primarily used when some data needs to be accessible by many components at different nesting levels. Apply it sparingly because it makes component reuse more difficult.

[Awesome React Context links](https://github.com/diegohaz/awesome-react-context)

1. **Consume content from (at least) two of the Awesome React Context links. Share your take-away from each:**
    1. **Takeaway 1:** [React's new context API: toggle between local and global state](https://www.freecodecamp.org/news/reacts-new-context-api-how-to-toggle-between-local-and-global-state-c6ace81443d0)
        * The React Context API involves Context, Provider, and Consumer. Context makes it easier to pass data globally across components. Context is used to pass and set state.
    2. **Takeaway 2:** [What’s new in React 16.3](https://medium.com/@baphemot/whats-new-in-react-16-3-d2c9b7b6193b)
        * Strict mode is a new way to make sure your code is following the best practices. It’s a component available under React.StrictMode and can be added to your application tree or subtree
        * The new context API is accessible as `React.createContext()` and creates two components: Provider and Consumer. The “Provider” is a special component which aims to provide data to all components in its sub-tree.
      The functions that will be in time considered deprecation are:
          * componentWillMount — please use componentDidMount instead
          * componentWillUpdate — please use componentDidUpdate instead
          * componentWillReceiveProps — a new function, static getDerivedStateFromProps is introduced
