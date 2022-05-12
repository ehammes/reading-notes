# Read: 04 - React and Forms

## Reading

### [React Docs - Forms](https://reactjs.org/docs/forms.html)

- **What is a ‘Controlled Component’?** An input form element whose value is controlled by React, controls what happens in the form upon user input
- **Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.** Update the state with the user's response as soon as they enter them because the React state is updated on every keystroke to display the value to the user.
- **How do we target what the user is entering if we have an event handler on an input field?** Add a name attribute to each element and let the handler function choose what to do based on the value of event.target.name

### [The Conditional (Ternary) Operator Explained](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)

- **Why would we use a ternary operator?** Shorter, cleaner code in one line
- **Rewrite the following statement using a ternary statement:**

```
if(x===y){
  console.log(true);
} else {
  console.log(false);
}
```

x===y ? console.log(true) : console.log(false)

#### **Bookmark and Review**

- [React Bootstrap - Forms](https://react-bootstrap.github.io/forms/overview/)
- [React Docs - conditional rendering](https://reactjs.org/docs/conditional-rendering.html)

##### Things I want to know more about

Working with forms in react
