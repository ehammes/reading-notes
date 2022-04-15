# Read: 10 - JS Debugging

via "HTML & CSS: Design and Build Websites" and "Javascript & JQuery: Interactive front-end web development" by Jon Duckett

## Readings

### JavaScript book, Ch. 10, “Error Handling & Debugging” (p.449-486)

JavaScript processes one line of code at a time. When a statement needs data from another function, it stacks/piles the new function on top of the current task. Execution context involves two phases of activity: **Prepare** (new scope created and variables, functions, and arguments created) and **Execute** (assign values to variables, reference functions and run code, execute statements). **Hoisting** occurs when: functions are called before they have been declared, value assigned to a variable that has not yet been declared. Each execution context has its own variables object in the interpreter. Functions have **lexical scope**, they are linked to the object they were defined *within*. Ideally variables are created within the function that is using them. 

#### Error Objects

An **exception** occurs when a JavaScript statement generates an error. An Error object contains the following properties: **name** type of execution, **message** description, **fileNumber** JS file, **lineNumber** of error. Built-in error objects include:

- **Error**: general error
- **SyntaxError**: syntax is not correct
- **ReferenceError**: variable does not exist
- **TypeError**: value is unexpected data type
- **RangeError**: number outside of range
- **URIError**: incorrect use of URI functions
- **EvalError**: incorrect use of eval() function

Deal with Errors by debugging the script to fix errors or handle errors gracefully. **Debugging** is the process of finding errors. Determine where the problem is: relevant script that caused the problem, the line number, type of error, console log to determine how far the script is running, use breakpoints where things are going wrong. There are multiple console methods that can be used: `console.info()`, `console.warn()`, `console.error()`, `console.group()`, `console.table()`, `console.assert()`.

##### Things I want to know more about

Learn and practice more ways to debug and fix errors. Tips/tricks on approaches in identifying errors.
