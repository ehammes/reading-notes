# Read: 06 - JS Object Literals; The DOM

via "HTML & CSS: Design and Build Websites" and "Javascript & JQuery: Interactive front-end web development" by Jon Duckett

## Readings

- **Understanding the problem domain is the hardest part of programming By John Sonmez**

What are some of the reasons for why writing code is difficult: Learning a new technology, Naming things, Testing your code, Debugging, Fixing bugs, Making software maintainable. Writing code is a lot like putting together a jigsaw puzzle. Understanding the problem is the most important aspect of writing code. Get better at understanding the problem and make the problem easier.

- **What’s the difference between primitive values and object references in JavaScript? By Chris Geelhoed**

Javascript's eight data types: Boolean, Null, Undefined, Number, BigInt, String, Symbol, Objects
Primitive values, object references

## Chapter 3: “Object Literals” (pp.100-105)

Objects group together a set of variables and functions to create a model of something. For objects, variables become known as properties (tell us about the object) and functions become known as methods. There are several ways to create objects. Properties or methods of an object can be accessed using dot notation.

## Chapter 5: “Document Object Model” (pp.183-242)

Browsers create a model of a page when it loads the page called its **DOM tree**. Each node is an object with methods and properties, scripts access and update the DOM tree. DOM trees have four types of nodes: document, element, attribute, and text. Accessing and updating the DOM tree involves locating via selecting and traversing. DOM queries may return one element, or they may return a NodeList, which is a collection of nodes.`getElementById()` and `querySelector()` can both search an entire document and return individual elements. Two ways to select an element from a NodeList: `item()` method and array syntax. There are two ways to add and remove content from a DOM tree: the **innerHTML** property and DOM manipulation. Utilize browser tools for viewing the DOM tree. `document.write()` is a simple way to add content, but it is not a recommended approach and is frowned upon. `element.innerHTML` allows you to get and update the entire content of any element (including markup) as a string. It should not be used to add content that has come from a user.

### Things I want to know more about

I need to further review the different approaches and methods for accessing, updating, and examining the DOM.
