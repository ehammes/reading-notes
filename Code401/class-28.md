# Read: 28 -  Component Lifecycle / useEffect Hook

## Reading

[effects hook](https://reactjs.org/docs/hooks-effect.html)

1. **What purpose does useEffect serve in a function component compared to its counterpart(s) in class components?** It is similar to `componentDidMount`, `componentDidUpdate`, and `componentWillUnmount` - performs side effects in components
2. **When using the useEffect Hook:**
    1. **What does useEffect do?** `useEffect` tells React that the component needs to do something after render - it will remember the function that was passed and call it later after performing the DOM updates.
    2. **Why is useEffect called inside a component?** It allows access to the count state variable (or any props) right from the effect.
3. **Explain the importance of properly implementing effects with Cleanup** Some side effects don't require cleanup while others do. Dependening on the setup, cleanup might be required to prevent adverse reactions such as introducing a memory leak when integrating to an external data source. With Hooks, if the effect returns a function, React will run it when it is time to clean up (when the component unmounts). React also cleans up effects from the previous render before running the effects next time.
