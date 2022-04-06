# Read: 03 - HTML Lists, CSS Boxes, JS Control Flow

via "HTML & CSS: Design and Build Websites" and "Javascript & JQuery: Interactive front-end web development" by Jon Duckett

## Chapter 3: “Lists” (pp.62-73)

- Ordered Lists: a numbered list
- Unordered Lists: bullet point lists
- Defiition Lists: a list of a set of terms along with each definition. Created with the `<dl>` element and `<dt>` is used to contain the term being definited (definition term) and `<dd>` is used to contain the definition. **Nested** lists can be created by putting a second list inside an `<li>` element.

**Ordered and unordered lists**: ordred lists use the `<ol>` element while unordered lists use the `<ul>` element. Each line item in the list is placed between an opening and closing tag using `<li>` aka list item.

## Chapter 13: “Boxes” (pp.300-329)

**Pixels**, **percentages**, or **ems** are used to specify the size of a box. **Min-width** and **max-width** specify the smallest and maximum widths. **Min-height** and **max-height** specify the minimum and maximum heights. The **overflow** property (hidden and scroll) tells the browser what to do if the content contained within a box is larger than the box itself. Every **box** has three available properties that can be adjusted to control its appearance:

1. **Border**: separates one box from another box

    - border-width: border width values include thin, medium and thick
    - border-top-width: you can control the individual size of borders using top, right, bottom, and left properties. The size of each border can be specified too.
    - border-style: border styles can be defined as solid, dotted, dashed, double, groove, ridge, inset, outset, hidden
    - border-color: specify the color of a border, can also indicate control individual borders top, right, bottom, left

2. **Margin**: margins sit outside the edge of the border, can create a gap between the borders of two adjacent boxes

     - If one box sits on top of another, margins are collapsed
     - Different values can be specified using margin-top, right, botton, left
     - shorthand (the values are in clockwise order): 10px 10px 5 px 5px

3. **Padding**: is the space between the border of a box and any content contained within it

    - Most often specifiedin pixels px, different values for each side can be definited using padding-top, right, bottom, left
    - shorthand (the values are in clockwise order): 10px 10px 5 px 5px

- To center a box on the page, set the left-margin and right-margin to auto.
- **Display**: turn an inline element into a block-level element or vice versa using inline, block, inline-block, and none. Use the vsiility property with hidden or visible to hide or show boxes.
- The **border-image** property applies an image to the border of the box. This property requires 1. the URL of the image 2. where to slice the image 3. what to do with the straight edges (stretch, repeat, round).
- The **box-shadow** property adds a drop shadow around the box. Horizontal offset (negative values), vertical offset (negative values), blur distance, and spread of shadow.
- Rounded Corners via **border-radius**

---

## Review from Reading 02 - Chapter 2: “Basic JavaScript Instructions” (pp.70-73)

An **Array** stores a list or a set of values that are related to each other. This can be done via array literal (preferred way) or array constructor. Array constructor is newArray() followed by values separated by commas.Each item in an array is automatically given a number called an **index**. **Note**: index values start at 0, not 1.

## Chapter 4: “Decisions and Loops” from switch statements on (pp.162-182)

A **switch** statement starts with a variable called the **switch value**. `switch()`statement has a **default** `default:` option that is run if noneo of the cases match. `break;` statement stops the rest of the switch statement running. The message is stored in a variable called **msg**.

Type coercion and weak typing
Truthy & Falsy values
Checking equality and existence
Short circuit values

**Loops** check a condition. If it returns **true**, a code block will run. It repeats until the condition returns **false**. Three common types of loops:

1. For: run code a specific number of times (most common type of loop), usually a counter. Create a variable, configure the condition (counter), counter is updated each time
2. While: the code will continue to loop for as long as the condition is true
3. Do While: it will always run the statements inside the curly braces at least once, even if the condition evaluates to false
