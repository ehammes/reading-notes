# Read: 07 - HTML Tables; JS Constructor Functions

via "HTML & CSS: Design and Build Websites" and "Javascript & JQuery: Interactive front-end web development" by Jon Duckett

## Readings:

## Domain Modeling ((GitHub)[https://github.com/codefellows/domain_modeling#domain-modeling])

Domain modeling is the process of creating a conceptual model for a specific problem. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model. Tips on building domain models:

1. When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
2. Model its attributes with a constructor function that defines and initializes properties.
3. Model its behaviors with small methods that focus on doing one job well.
4. Create instances using the `new` keyword followed by a call to a constructor function.
5. Store the newly created object in a variable so you can access its properties and methods from outside.
6. Use the `this` variable within methods so you can access the object's properties and methods from inside.

## Chapter 6: “Tables” (pp.126-145)

A **table** represents information in a grid report. Each bock in the grid is referred to as a **table cell**. Basic table structure includes:

- **`<table>`**: used to create a table
- **`<tr>`**: table row, used at the start of each row
- **`<td>`**: table data, used for each cell of a table
- **`<th>`**: table heading, used to represent the heading for either a column or a row
- The `colspan` attribute (ie. "`<td colspan="2">) can be used on a th or td element and indicates how many colunms that cell should span across.
- The `rowspan` attribute (ie. "`<td rowspan="2">) can be used on a th or td element and indicates how many rows a cell should span down the table.
- **`<thead>`**: headings of a table should sit inside this element
- **`<tbody>`**: the body should sit inside this element
- **`<tfoot>`**: the footer belongs in this element. Using these elements will keep the header and footer visibile whilst the content of the table scroll.
- Old Code: using width attribute on the table, th, and td tags to specify width. Cellpadding on the table tag. Border and background attributes (CSS should be used instead)

## Chapter 3: “Functions, Methods, and Objects” (pp.106-144)

The new keyword and the object constructor create a blank object. Properties and methods can be added to the object. Use literal notation to create an empty object `var hotel = {}`. To update the value of properties, use dot notation or square brackets (ie. `hotel.name = 'Park` - hotel is object, name is property name, and Park string is property value).

---

**Contructor Notation**: The constructor function is used to create **instances** of the object. The **new** keyword followed by a call to the cuntion creates a new object. The properties of each object are given as arguments to the function. Use the **new** keyword when creating an object using the constructor funciton. The name of a constructor function usually begins with a capital letter. The += operator is used to add content to an existing variable. Add properties using dot notation, delete a property using the **delete** keyword. Objects can be created through Literal Notation and Object Constructor Notation.

**Global Scope or Global Context**: when a function is created at the top level of a script.

Arrays are a special type of object. Arrays and objects can be combined. Browsers come with a set of built-in objects, such as browser window, current web page, etc: Browser object model, document object mode, global javascript objects. Use the **Date** object when working with dates.