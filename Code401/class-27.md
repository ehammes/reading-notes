# Read: 27 - useState() Hook

## Reading

[Introducing Hooks](https://reactjs.org/docs/hooks-intro.html#motivation)

1. **What was the motivation for introducing Hooks?** Hooks solve a wide variety of seemingly unconnected problems in React. With Hooks, you can extract stateful logic from a component so it can be tested independently and reused. Hooks allow you to reuse stateful logic without changing your component hierarchy. This makes it easy to share Hooks among many components or with the community. Complex components require to jump between files, more likelihood of bugs, harder to test.
2. **What changes are important regarding implementing Hooks versus Component Classes?** Hooks let you split one component into smaller functions based on what pieces are related.
3. **Hooks allow you to reuse stateful logic without changing ___ _______.** component hierarchy

[hooks api](https://reactjs.org/docs/hooks-overview.html)

1. **Name two rules imposed by React Hook usage.**
    1. Only call Hooks at the top level. Don’t call Hooks inside loops, conditions, or nested functions.
    2. Only call Hooks from React function components. Don’t call Hooks from regular JavaScript functions.
2. **How would you identify a custom Hook and why might you create one?** Function starts with `use` and calls other hooks

[the state hook](https://reactjs.org/docs/hooks-state.html)

1. **What is a Hook?** A Hook is a special function that lets you “hook into” React features. For example, useState is a Hook that lets you add React state to function components.
2. **When would I use the useState Hook?** useState is a Hook that lets you add React state to function components.
3. **If you were to add React state to a function component by declaring a state variable:**
    1. **What does calling useState do?** It declares a state variable. useState is a new way to use the exact same capabilities that this.state provides in a class
    2. **What do we pass to useState as an argument?** Only the initial state
    3. **What does useState return?** It returns a pair of values: the current state and a function that updates it

### Bookmark and Review

- [hooks api reference](https://reactjs.org/docs/hooks-reference.html)
