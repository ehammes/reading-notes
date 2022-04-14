# Read: 09 - Forms and Events

via "HTML & CSS: Design and Build Websites" and "Javascript & JQuery: Interactive front-end web development" by Jon Duckett

## Readings

### Chapter 7: “Forms” (p.144-175)

Forms allow users to input information there are different types of form controls: adding text, making choices (radio buttons, checkboxes, drop-downs), and submitting forms. Various pieces of inputted data need to be differentiated to understand the name and value. Form controls live inside a **form** element and includes action and ID attributes. Forms are sent using get or post. Most forms will use the post method (sent in HTTP headers) because they contain files, sensitive information, long forms. The get method adds the values to the end of the URL specified in the action attribute. Example of input: `<input type="text" name="username" size="15" maxlength="30"/>` (all within a form tag). Max length limits the number of characters entered into the field. Type "password" blocks out the characters typed into the form field. **Text Area** is used to create a multi-line text input. Input type **radio** creates radio button options, example:`<input type="radio" name="genre" value="jazz"/>`with each option listed as a separate radio type. Overall, input types include: password, text area, radio button, checkbox. The **select** element is used to create a drop down list box (aka select box). The **option** element is used to define the values and the **multiple** element is used to allow for multi select. The input type **file** allows for file upload and the **submit** type adds a submit button. An image can be inserted for a button by using the input type **image**. Form elements can be grouped by using the **fieldset** element. Form validation is typically done via Javascript. Type **date** is used to have a date value in a form input. Additional type inputs include: email, URL, search. Placeholder text can be added to a field using the **placeholder** attribute.

### Chapter 14: “Lists, Tables & Forms” (pp.330-357)

There are multiple types of list styles:

- **Bullet points**: the **list-style-type** property allows to control the shape or style of a bullet point - unordered lists or ordered lists.
- **Images** for bullets: using the **list-style-image** property
- **Positioning** the marker: the **list-style-position** property is used to define if the marker is on the inside or the outside of the box
- **List Shorthand**: **list-style** is used to express the marker's style, image and position properties in any order

#### Styling

- **Table Properties** include: width, padding, text-transform, letter-spacing, font-size, border-top, border-bottom, text-align, background-color, :hover, add borders and gaps between cells
- **Forms and Inputs** can be styled using font-size, color, background-color, border, border-radius, :focus, :hover, background-image
- **Submit buttons**: color, text-shadow, border-buttom, background-color, :hover
- **Fieldsets and Legends**: width, color, background-color, border, border-radius, padding
- **Aligning forms**: use div, label, span elements to align text and controls
- **Cursor**: within the a property in CSS - auto, crosshair, default, pointer, move, text, wait, help, URL

### Chapter 6: “Events” (pp.243-292)

There are several different event types: UI, keyboard, mouse, focus, mutation. Events are described as fired, raised, or triggered. There are steps involed to trigger events: select the element nodes you want the script to respond to, indicate which event will trigger the response, and state the code you want executed when the event occurs. **Select, specify, and call code**. **Event Listeners** can deal with multiple functions at a time but are not supported in older browsers (such as IE). Parameters are used within event handlers and listeners.

---

**Event Flow**: the flow of elements matter when your code has event handlers on an element *and* one of its ancestor or descendant elements. The **Event Object** tells you information about the event and the lement it happened upon. Different types of events include: W3C, HTML5, BOM, UI, load, focus & blur, mouse (click), keyboard, forms, mutation (struture changes in DOM). The most commonly used events are W3C DOM. Event delegation can be used to monitor for events that happen on all of the children of an element.
