# Programming with JavaScript Notes

## Control Flow

The control flow is the order in which the computer executes statements in a script.
Code is run in order from the first line in the file to the last line, unless the computer runs across the (extremely frequent) structures that change the control flow, such as conditionals and loops.
A condition is a set of rules that can interrupt normal code execution or change it, depending on whether the condition is completed or not.
An instruction or a set of instructions is executed if a specific condition is fulfilled. Otherwise, another instruction is executed. It is also possible to repeat the execution of an instruction, or set of instructions, while a condition is not yet fulfilled.

## JavaScript Functions

- A JavaScript function is a block of code designed to perform a particular task.
- A JavaScript function is executed when "something" invokes it (calls it).
- A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses ().
- Function names can contain letters, digits, underscores, and dollar signs (same rules as variables).
- The parentheses may include parameter names separated by commas:(parameter1, parameter2, ...)
- The code to be executed, by the function, is placed inside curly brackets: {}
- Function **parameters** are listed inside the parentheses () in the function definition.
- Function **arguments** are the **values** received by the function when it is invoked.
- Inside the function, the arguments (the parameters) behave as local variables.

### Function Invocation

The code inside the function will execute when "something" **invokes** (calls) the function:

- When an event occurs (when a user clicks a button)
- When it is invoked (called) from JavaScript code
- Automatically (self invoked)

**Function Return**
When JavaScript reaches a return statement, the function will stop executing.
If the function was invoked from a statement, JavaScript will "return" to execute the code after the invoking statement
Functions often compute a **return value**. The return value is "returned" back to the "caller"

### Javascript Operators

- The **assignment** operator (=) assigns a value to a variable.
- The addition operator (+) adds numbers
- The multiplication operator (*) multiplies numbers.
- The addition assignment operator (+=) adds a value to a variable.
- The += assignment operator can also be used to add (concatenate) strings

| **Operator** | **Description** |
| + | Addition |
| - | Subtraction |
| * | Multiplication |
| ** | Exponentiation |
| / | Division |
| % | Modulus  |
| ++ | Increment |
| -- | Decrement |

### Functions

**Functions** are one of the fundamental building blocks in JavaScript. A function in JavaScript is similar to a procedure—a set of statements that performs a task or calculates a value, but for a procedure to qualify as a function, it should take some input and return an output where there is some obvious relationship between the input and the output. To use a function, you must define it somewhere in the scope from which you wish to call it.

A **function definition** (also called a function declaration, or function statement) consists of the function keyword, followed by:

- The name of the function.
- A list of parameters to the function, enclosed in parentheses and separated by commas.
- The JavaScript statements that define the function, enclosed in curly brackets, {...}.
The function square takes one parameter, called number. The function consists of one statement that says to return the parameter of the function (that is, number) multiplied by itself. The statement return specifies the value returned by the function

For more, see [Operators](https://www.w3schools.com/js/js_operators.asp), [Expressions and Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators), and [Functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)
