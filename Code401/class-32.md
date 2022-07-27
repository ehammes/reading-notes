# Read: 32 - Context API - Behaviors

## Reading

[Hooks and Context example](https://medium.com/swlh/snackbars-in-react-an-exercise-in-hooks-and-context-299b43fd2a2b)

1. **With regard to the React Context API, what does a “provider” do?** Allows state to be globally accessible
2. **With regard to the React Context API, how would we implement a “consumer” role?** A wrapper around the `useContext` internal React Hook
3. **Specifically with Context, how are we “wrapping” components to achieve our goals?** To consume the new content, components are wrapped

[Awesome React Context links](https://github.com/diegohaz/awesome-react-context)

1. **Consume content from (at least) two more of the Awesome React Context links. After some familiarity with React Context, once again share your takeaways from each:**
    1. **Takeaway 1:** [React-loadable-context](https://github.com/crubier/react-loadable-context)
        - The function returns: A Provider, which injects the loaded object into the context as soon as the promise is resolved AND Various Consumer components, which gracefully handle loading and error states. The main "wrapper" component for the library uses the Provider. The various "elements" of the library use the Consumer.
    2. **Takeaway 2:** [React-broadcast](https://github.com/ReactTraining/react-broadcast/tree/next)
        - react-broadcast provides a reliable way for React components to propagate state changes to their descendants deep in the component hierarchy, bypassing intermediaries who return false from shouldComponentUpdate.
        - It was originally built to solve issues that arose from using react-router together with react-redux. The router needed a safe way to communicate state changes to <Link>s deep in the component hierarchy, but react-redux relies on shouldComponentUpdate for performance. react-broadcast allows the router to work seamlessly with Redux and any other component that uses shouldComponentUpdate.
