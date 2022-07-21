# Read: 29 -  Advanced State with Reducers

## Reading

[useReducer hook](https://reactjs.org/docs/hooks-reference.html#usereducer)

1. **Name an alternative to the useState Hook.** useReducer, accepts a reducer of type (state, action) => newState, and returns the current state paired with a dispatch method.
2. **Why might the useReducer Hook be preferable to the useState Hook?** useReducer is usually preferable to useState when you have complex state logic that involves multiple sub-values or when the next state depends on the previous one. useReducer also lets you optimize performance for components that trigger deep updates because you can pass dispatch down instead of callbacks.
3. **What are two ways to set the initial state?** Pass the initial state as a second argument or pass an init function as a third argument 'lazy initialization' (lets you extract the logic for calculating the initial state outside the reducer)

[Ultimate Guide to useReducer](https://blog.logrocket.com/guide-to-react-usereducer-hook/)

1. **In terms of state, what does useReducer expect to receive as a parameter?** a reducer function and the initial state
2. **What does useReducer return?** Returns an array that holds the current state value and a dispatch function to which you can pass an action and later invoke it.
3. **Explain dispatch to a non-technical recruiter.** Dispatch represents the type of action you want to perform - it sends this action to the reducer function to execute the action (updating state)
