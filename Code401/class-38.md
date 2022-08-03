# Read: 38 - Redux - Asynchronous Actions

## Reading

[async actions](https://redux.js.org/advanced/asyncactions)

1. **Why use Redux middleware?** Redux middleware were designed to enable writing logic that has side effects. A Redux middleware can do anything when it sees a dispatched action: log something, modify the action, delay the action, make an async call, and more. Middleware also have access to dispatch and getState. That means you could write some async logic in a middleware, and still have the ability to interact with the Redux store by dispatching actions.
2. **Consider the Redux Async Data Flow Diagram. Describe the flow in your own words.** A user event happens in the application and then we call `dispatch()`, and pass in something, whether it be a plain action object, a function, or some other value that a middleware can look for. Once that dispatched value reaches a middleware, it can make an async call, and then dispatch a real action object when the async call completes.
3. **How are we accommodating async in our Redux app?** The thunk middleware allows us to write functions that get `dispatch` and `getState` as arguments. The thunk functions can have any async logic we want inside, and that logic can dispatch actions and read the store state as needed. Writing async logic as thunk functions allows us to reuse that logic without knowing what Redux store we're using ahead of time.

[thunk middleware](https://github.com/reduxjs/redux-thunk)

1. **Why would you need redux-thunk middleware?** Thunks are the recommended middleware for basic Redux side effects logic, including complex synchronous logic that needs access to the store, and simple async logic like AJAX requests.
2. **Redux Thunk middleware allows you to write action creators that return a `function` instead of an action.**
3. **Describe how any return value from the inner thunk function will be made available.** Any return value from the inner function will be available as the return value of `dispatch` itself. This is convenient for orchestrating an asynchronous control flow with thunk action creators dispatching each other and returning Promises to wait for each other’s completion.
