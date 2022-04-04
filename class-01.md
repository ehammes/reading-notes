# Read: 01 - Introductory HTML and JavaScript

## Introduction to HTML (pp.2-11)

## HTML Chapter 1: “Structure” (pp.12-39)

## HTML Chapter 8: “Extra Markup” (p.176-199)

## HTML Chapter 17: “HTML5 Layout” (pp.428-451)

## HTML Chapter 18: “Process & Design” (pp.452-475)

-

## Introduction to Javascript

Learning to program with JS involves:

1. Understanding some **brasic programming concepts** and the terms that JS programmers user to describe them
2. Learning **the language** itself, and, like all languages, you need to know its vocabulary and how to structure your sentences
3. Becoming familiar with **how it is applied** by looking at examples of how JS is commonly used in websites today.

How Javascript makes web pages more interactive:

1. **Access** content - to select any element, attirbute, or text from an HTML page
2. **Modify** content - to add elements, attributes, and text to the page, or remove them
3. **Program** Rules - specify a set steps for the browser to follow, which allows it to access or change the content of a page
4. **React** to Events - specify that a script should run when a specific event has occurred

-

## JS Chapter 1: “The ABC of Programming” (pp.11-52)

- **A**: What is a script and how do I create one?
- **B** How do computers fit in with the world around them?
- **C** How do I write a script for a web page?

A **script** is a series of instructions that a computer can follow to achieve a goal. Examples include comparing scripts to receipes, handbooks, and manuals. Each time the script runs, it might only use a subset of all the instructions. Computers approach tasks programmatically. To approach writing a script, break down your goal into a series of tasks.

To write a **script**, you need to first staate your goal and then list the tasks that need to be completed in order to achieve it:

1. Define the goal
2. Design the script
3. Code each step

Use *flowcharts* to work out how the different tasks fit together.

Each physical thing in the world can be represented as an **object**. Each object can have its own properties, events, and methods. Each **property** of an object has a **name** and a **value**. When a specific **event** happens, that event can be used to trigger a specific section of the cose. **Methods** represent things people need to do with objects. The **events**, **models**, and **properties** of a object all relate to each other. Events can trigger methods, and methods can retrieve or update an object's properties.

Types of objects include:

- Window
- Document

### How a browser sees a web page**

1. Receive a page as HTML code
2. Create a model of the page and store it in memory
3. Use a rendering engine to show the page on screen

### How HTML, CSS, & Javascript fit together

Content Layer - .html files, gives the page structure and adds semantics
Presentation Layer - .css files, enhances the HTML page with rules that state how the HTML content is presented
Behavior Layer - .js files, how the page behaves, adding interactivity

Whwn you want to use JavaScript with a web page, you use the HTML `<script>` element to tell the browser it is coming across a script. Its src attribute tells people where the JavaScript file is stored. You may see JavaScript in the HTML between opening `<script>` and closing tags, but it is better to put scripts in their own files.

`document.write('Good afternoon!')` - the **document** object represents the entire web page. The `write()` method of the **document** object allows new content to be written in to the page where the `<script>` element sits. Each piece of intformation is called a **parameter** of the method and the method needs to know what to write to the page. When the browser comes across a `<script>` element, it stops to load the script and then checks to see if it need to do anything.

#### Things I want to know more about
