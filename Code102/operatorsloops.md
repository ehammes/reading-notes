# Expressions and Operators; Loops

## Expressions and Operators

## Assignment Operators

[Expressions and Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)
An **assignment operator** assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. That is, x = f() is an assignment expression that assigns the value of f() to x.

Name | Shorthand operator | Meaning
Assignment | x = f() | x = f()
Addition assignment | x += f() | x = x + f()
Subtraction assignment | x -= f() | x = x - f()
Multiplication assignment | x *= f() | x = x * f()
Division assignment | x /= f() | x = x / f()
Remainder assignment | x %= f() | x = x % f()
Exponentiation assignment | x **= f() | x = x ** f()
Left shift assignment | x <<= f() | x = x << f()
Right shift assignment | x >>= f() | x = x >> f()
Unsigned right shift assignment | x >>>= f() | x = x >>> f()
Bitwise AND assignment | x &= f() | x = x & f()
Bitwise XOR assignment | x ^= f() | x = x ^ f()
Bitwise OR assignment | x |= f() | x = x | f()
Logical AND assignment | x &&= f() | x && (x = f())
Logical OR assignment | x ||= f() | x || (x = f())
Logical nullish assignment | x ??= f() | x ?? (x = f())

**Assigning to Properties**: If a variable refers to an object, then the left-hand side of an assignment expression may make assignments to properties of that variable.
**Evaluating and Nesting**: In general, assignments are used within a variable declaration (i.e., with const, let, or var) or as standalone statements). By chaining or nesting an assignment expression, its result can itself be assigned to another variable. It can be logged, it can be put inside an array literal or function call, and so on. The evaluation result matches the expression to the right of the = sign in the "Meaning" column of the table above. That means that x = f() evaluates into whatever f()'s result is, x += f() evaluates into the resulting sum x + f(), x **= f() evaluates into the resulting power x ** y, and so on.
In the case of logical assignments, x &&= f(), x ||= f(), and x ??= f(), the return value is that of the logical operation without the assignment, so x && f(), x || f(), and x ?? f(), respectively.
When chaining these expressions without parentheses or other grouping operators like array literals, the assignment expressions are grouped right to left (they are right-associative), but they are evaluated left to right.

**Avoid Assignment Chains**: Chaining assignments or nesting assignments in other expressions can result in surprising behavior. For this reason, chaining assignments in the same statement is discouraged

## Comparison Operators

A **comparison operator** compares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, string, logical, or object values. Strings are compared based on standard lexicographical ordering, using Unicode values. In most cases, if the two operands are not of the same type, JavaScript attempts to convert them to an appropriate type for the comparison. This behavior generally results in comparing the operands numerically. The sole exceptions to type conversion within comparisons involve the === and !== operators, which perform strict equality and inequality comparisons. These operators do not attempt to convert the operands to compatible types before checking equality.

Operator | Description | Examples returning true
Equal (==) | Returns true if the operands are equal. | 3 == var1 "3" == var1 3 == '3'
Not equal (!=) | Returns true if the operands are not equal. | var1 != 4 var2 != "3"
Strict equal (===) | Returns true if the operands are equal and of the same type. See also Object.is and sameness in JS. | 3 === var1
Strict not equal (!==) | Returns true if the operands are of the same type but not equal, or are of different type. | var1 !== "3" 3 !== '3'
Greater than (>) | Returns true if the left operand is greater than the right operand. | var2 > var1 "12" > 2
Greater than or equal (>=) | Returns true if the left operand is greater than or equal to the right operand. | var2 >= var1 var1 >= 3
Less than (<) | Returns true if the left operand is less than the right operand. | var1 < var2 "2" < 12
Less than or equal (<=)	Returns true if the left operand is less than or equal to the right operand. | var1 <= var2 var2 <= 5

## Loops and Interation

[Loops](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration)

### For Statements

A **for** loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop.
A **for** statement looks as follows:
for ([initialExpression]; [conditionExpression]; [incrementExpression])
When a for loop executes, the following occurs:

1. The initializing expression initialExpression, if any, is executed. This expression usually initializes one or more loop counters, but the syntax allows an expression of any degree of complexity. This expression can also declare variables.

2. The conditionExpression expression is evaluated. If the value of conditionExpression is true, the loop statements execute. Otherwise, the for loop terminates. (If the conditionExpression expression is omitted entirely, the condition is assumed to be true.)

3. The statement executes. To execute multiple statements, use a block statement ({ ... }) to group those statements.

4. If present, the update expression incrementExpression is executed.

5. Control returns to Step 2.

### While Statements

A **while** statement executes its statements as long as a specified condition evaluates to true. A while statement looks as follows:

while (condition)
  statement
If the condition becomes false, statement within the loop stops executing and control passes to the statement following the loop.

The condition test occurs before statement in the loop is executed. If the condition returns true, statement is executed and the condition is tested again. If the condition returns false, execution stops, and control is passed to the statement following while.

To execute multiple statements, use a block statement ({ ... }) to group those statements.
