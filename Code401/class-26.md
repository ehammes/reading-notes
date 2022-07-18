# Read: 26 - Component Based UI

## Reading

[react hello world](https://facebook.github.io/react/docs/hello-world.html)

1. **What are the building blocks of a React app?** Elements, they represent the UI at a certain point in time. Components
2. **What is the difference between an element and a React component?** Components split the UI into independent, reusable pieces. Components are like javascript functions. Elements are what components are made of.
3. **What are some advantages of React’s component based architecture?** Components are reusable and code is modular and easier to read.

[introducing JSX](https://facebook.github.io/react/docs/introducing-jsx.html)

1. **What is JSX and why do we use it?** JSX is a syntax extension to JavaScript. It is used with React to describe what the UI should look like. JSX produces React “elements”. Most people find it helpful as a visual aid when working with UI inside the JavaScript code. It also allows React to show more useful error and warning messages.
2. **Describe the process of embedding JavaScript expressions in JSX.** You can put any valid JavaScript expression inside curly braces in JSX.
3. **Is it safe to embed user input in JSX? Explain.** Yes, it is safe to embed user input in JSX. Everything is converted to a string before being rendered. This helps prevent XSS (cross-site-scripting) attacks.

[rendering elements](https://facebook.github.io/react/docs/rendering-elements.html)

1. **Explain what a React Component is to a non-technical friend.** React components represent different sections of your UI, essentially a template. Components are reusable throughout an app.
2. **Describe mutability and React Components, specifically, how is the UI updated?** Once React Elements are created, you can’t change its children or attributes. The only way to update the UI is to create a new element, and pass it to root.render().
3. **If changes are made to the UI, what does React update?** React DOM compares the element and its children to the previous one, and only applies the DOM updates necessary to bring the DOM to the desired state.

### Bookmark and Review

- [sass cheatsheet](https://devhints.io/sass)
- [react cheatsheet](https://devhints.io/react)
- [another react cheatsheet](https://reactcheatsheet.com/)
