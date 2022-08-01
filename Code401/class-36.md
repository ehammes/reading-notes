# Read: 36 - Application State with Redux

## Reading

[Dan Abramov Redux Tutorials](https://egghead.io/courses/getting-started-with-redux)

1. **What is the first principle of Redux?** Represent the entire state of the application as a single javascript object
2. **What is a store and what do we use our reducers for within that store?** A store brings together the state, actions, and reducers of an app. A reducer takes in the previous state and an action and return the newly updated state.
3. **Name three Redux store methods given to us by createStore and describe their use.**
    * `getState()`: retrieves the current state of the Redux chore
    * `dispatch()`: commonly used, dispatches actions to change the state of the application
    * `describe()`: registers a callback that the Redux chore will dispatch anytime it is called so that the UI of the application can be updated to reflect the current application state.
4. **Explain to a non-technical recruiter what cc does and why it is useful.** As an application grows and becomes more complex, the app can have multiple reducers each managing independent parts of the state. The combineReducers() helper function turns an object whose values are different reducing functions into a single reducing function that can be passed to createStore().

### Bookmark and Review

* [worlds easiest guide to redux](https://medium.freecodecamp.org/understanding-redux-the-worlds-easiest-guide-to-beginning-redux-c695f45546f6)
* [testing reducers](https://medium.com/@netxm/testing-redux-reducers-with-jest-6653abbfe3e1)
* [Redux Docs](https://redux.js.org/)
