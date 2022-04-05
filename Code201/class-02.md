# Read: 02 - HTML Text, CSS Introduction, and Basic JavaScript Instructions

via "HTML & CSS: Design and Build Websites" and "Javascript & JQuery: Interactive front-end web development" by Jon Duckett

## Chapter 2: “Text” (pp.40-61)

- HTML has six "levels" of headings (h1 to h6)
-`<p>`: create a paragraph
-`<b>`: bold
-`<i>`: italic
-`<sup>`: superscript
-`<sub>`: subscript
-`<br>`: line break
-`<hr>`: horizontal rule
-`<strong>`: bold
-`<em>`: emphasis / italics
-`<blockquote>`: used for longer quotes
-`<q>`: used for shorter quotes within a paragraph
-`<abbr>`: used for abbreviations
-`<cite>`: used for citations
-`<dfn>`: used to indicate the defining instance of a new term
-`<address>`: contains contact details for the auothor of th epage
-`<ins>` and `<del>`: to show content that has been inserted or deleted to/from a document.
-`<s>`: represents something that is no longer accurate or relevant

If a browser comes across two or more spaces next to each other, it only displays one space.
Text elements that add extra information to the page, but don't affect the structure of your web pages are known as **semantic markup**.

## Chapter 10: Ch.10 “Introducing CSS” (pp.226-245)

CSS **Selectors** indcate which element the rule applies to while **declarations** indicate how the lements referred to in the selector should be styled. Declarations sit inside curly brakcets and each is made up of two parts: a **property** and a **value**, separated by a colon. Properties indicate the aspects of the element you want to change while values specify the settings you want to use for the chosen properties.

For `<link>` involves href (specifies the path to the CSS file), type (specifies the type of document being linked to), and rel (specifies the relationship betweeen the HTML page and the file it is linked to).

Types of CSS Selectors:

- Universal: applies to all elements in the document
- Type: matches element names
- Class: Matches an element whose class attribute has a value that matches the one specified after the period (or full stop) symbol
- ID: Matches an element whose id attribute has a value that matches the one specified after the point or has sign
- Child: matches an element that is a direct child of another
- Descendant
- Adjacent sibling
- General sibling

---

## Chapter 2: “Basic JavaScript Instructions” (pp.53-84)

A **script** is a series of instructions that a computer can follow one-by-one. A script will have to temporarily store the bits of information it needs to do its job. It can store this data in **variables**.
Javascript is case sensitve.
You should write comments to explain what your code does. Multi-line comments can be done through using `/* */`
Variables must be declared and assigned a value: **variable keyword**, **variable name**, and **variable value**.
Data types include: numeric, string, and boolean
**backwards slash** (/) tells the interpreter that the following chharacter is part of the string, rather than the end of it.

**Six rules for naming variabeles**:

1. Name must begin with a letter, dollar sign, or an underscore. It must not start with a number.
2. Name must not use a dash or period
3. Name cannot use keywords or reserved words
4. All variables are case sensitive
5. Use a name that desscribes the kind of information that the variable stores.
6. Use camel case for multiple words in a variable

An **expression** evaluates into (results in) a single value. There are two types of expressions: assign a value to a variable or use two or mor eavlues to return a signle value.

**Operators** create a single value from one or more values. Arithmetic operators are used with numbers.

## Chapter 4: “Decisions and Loops”(pp.145-162)

Two components of a decision: an expression is evaluated and returns a value AND a conditional statement says what to do in a given situation. The operand does not have to be a single value or variable name. An operand can be an *expression* because each expression evaluates into a single value. Comparison operators usually return single values of ture or false. Logical expresions are evaluated left ot right.

&& (Logical AND) - tests more than one condition
|| (Logical OR) - tests at least one condition
! (Logical NOT) - takes a single Boolean value and inverts it

The **if** statement evaluates or checks a condition.
The **if...else** statement checks a condition. If it resolves to true the first code block is executed. If the condition resolves to false the second code block is run instead.

## Things I want to know more about

Need to practice different decisions and loops
