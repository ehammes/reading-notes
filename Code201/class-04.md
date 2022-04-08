# Read: 04 - HTML Links, CSS Layout, JS Functions

via "HTML & CSS: Design and Build Websites" and "Javascript & JQuery: Interactive front-end web development" by Jon Duckett

## Chapter 4: Ch.4 “Links” (pp.74-93)

Links are created with `<a>` tag and **href** attribute is used to specify the URL (Uniform Resource Locator) of the page - the full URL called the **absolute** URL. The link text is listed in the `<a>` tags. You can use a short hand URL when linking to a page within the same site, called a **relative** URL. On larger websites its a good idea to organize your code by placing the pages for each different section into a new folder.

### Directory Structure

- Structure - top level folder is known as the **root**
- Relationships - folder structure includes parent and children
- Homepage - the main homepage file is called index.html
- Relative link types - same folder, child folder, grandchild folder, parent folder, grandparent folder

Email links will open up into a user's email client using **mailto:**. **Target** is used to open links into a new window (ie points to a different website). ID attributes are used to link to different parts of a page.

## Chapter 15: “Layout” (pp.358-404)

- Note: This layout chapter is BIG. Focus your attention on understanding the core concepts presented on pp.358-364, and look at the code samples on the website that accompanies the textbook. You will have another reading assignment on this chapter, so do not try to digest it all now.

**Building Blocks** - Each HTML element is treating as its own box. The box will either be a block-level box (starts on a new line) or inline box (flows in between surrounding text). If one block-level element sits within another, the outer box is known as the **containing** or **parent** element.

### Positioning Schemes

- Normal Flow: every block-level element appears on a new line
- Relative Positioning: this moves an element from the position it would be in normal flow
- Absolute Positioning: this positions the element in relation to its containing element. Fixed positioning positions the element in relation to the browser. Floating allows to take the element out of normal flow and position it to the far left or far right of a containing box.

You may have to use **box offset** properties to indicate to the browser how far the positioning should be place. The z-index property allows you to control which appears on top.

---

## Chapter 3 (first part): “Functions, Methods, and Objects” (pp.86-99 ONLY)

### Function

**Functions** allow you to group a series of statements together to performa a specific task. You can reuse the function if different parts of the script repeat the same tasks. Pieces of information passed to a function are called **parameters**. The **return value** is the output of the function. A function **declaration** is required using the function keywords, name, and statements. **Calling the function** is done by using the function name, this executes the statements in the function. Parameters are are listed within the function. When calling a function, the **arguments** are listed for the function to use. Functions can return more than one value using an array. The location where you declare your variables matters, if its within the function then it can only be used for that function. This is known as the variable's **scope**.

## Article: “6 Reasons for Pair Programming”

**The Driver** is the programmer who is typing and the only one whose hands are on the keyboard. Handling the “mechanics” of coding, the Driver manages the text editor, switching files, version control, and—of course writing—code. **The Navigator** uses their words to guide the Driver but does not provide any direct input to the computer.

### Four Fundamental Skills in learning a new language

- **Listening**: hearing and interpreting the vocabulary
- **Speaking**: using the correct words to communicate an idea
- **Reading**: understanding what written language intends to convey
- **Writing**: producing from scratch a meaningful, well structured solution

### Pair Programming

1. Greater Efficiency
2. Engaged Collaboration
3. Learning from fellow students
4. Social Skills
5. Job Interview Readiness
6. Work Environment Readiness
