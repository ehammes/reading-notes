# Read: 10 - In memory storage

## Reading

### [Understanding the JavaScript Call Stack](https://medium.freecodecamp.org/understanding-the-javascript-call-stack-861e41ae61d4)

- **What is a ‘call’?** Function invocation
- **How many ‘calls’ can happen at once?** A call stack is synchronous and a function execution is done one at a time from top to botton
- **What does LIFO mean?** Last In, First Out. The last function that gets pushed into the stack is the first to be popped out, when the function returns. When a function is invoked (called), the function, its parameters, and variables are pushed into the call stack to form a stack frame. This stack frame is a memory location in the stack. The memory is cleared when the function returns as it is pop out of the stack. **A call stack** is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).
- **Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.**

```
function firstFunction(){
  console.log("Hello from firstFunction");
}

function secondFunction(){
  firstFunction();
  console.log("The end from secondFunction");
}

secondFunction();
```

- **What causes a Stack Overflow?** A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.

#### [JavaScript error messages](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)

- **What is a ‘reference error’?** Using an error that has not been declared
- **What is a ‘syntax error’?** Something that cannot be parsed in terms of syntax
- **What is a ‘range error’?** An error when a value is not in the set or range of allowed values
- **What is a ‘tyep error’?** When the types (number, string, etc.) that are being used or accessed are incompatible, such as accessing a property in an undefined type of variable
- **What is a breakpoint?** Allows a user to see what has happened before that line/point and evaluates the next lines to check if everything is outputting as expected.
- **What does the word ‘debugger’ do in your code?** Creates a breakpoint and helps with debugging code. Will display the history details before reaching the breakpoint.

#### [Bookmark and Review](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors)

- [JavaScript errors reference on MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors)
