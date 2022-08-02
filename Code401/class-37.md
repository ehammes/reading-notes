# Read: 37 - Redux - Combined Reducers

## Reading

[Multiple Reducers Example](https://www.youtube.com/watch?v=gBER4Or86hE)

1. **Why create multiple reducers?** Easier to manage
2. **How would you combine multiple reducers?** Import `combineReducers` and pass in an object that specifies the reducers that will manage state
3. **How will you manage state as an immutable object? why?** Return a new state object

[Redux Docs: Using Combined Reducers](https://redux.js.org/recipes/structuring-reducers/using-combinereducers/)

1. **`combineReducers` is a utility function to simplify the most common use case when writing ___ _____ .** Redux reducers
2. **Explain how `combineReducers` assembles the new state tree.** `combineReducers` will call each slice reducer with its current slice of state and the current action, giving the slice reducer a chance to respond and update its slice of state if needed.
3. **How would you define initial state in an app using `combineReducers`?**

    - The `createStore` function can take preloadedState as its second argument
    - The other way is for the root reducer to return the initial state value when the state argument is undefined.

[Redux Docs: Combined Reducer Syntax](https://redux.js.org/api/combinereducers/)

1. **Why will you want to split your reducing functions as your app becomes more complex?** When the app becomes more complex, it is easier to manage independent parts of state by splitting out the reducing function
2. **The `combineReducers` helper function turns an object whose values are different reducing functions into a single reducing function you can pass to `createStore`.**
3. **What is a popular convention when naming reducers?** Name reducers after the state slices they manage, for example `combineReducers({ counter: counter, todos: todos })`
