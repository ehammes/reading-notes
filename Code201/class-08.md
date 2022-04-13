# Read: 08 - More CSS Layout

via "HTML & CSS: Design and Build Websites" and "Javascript & JQuery: Interactive front-end web development" by Jon Duckett

## Readings

### Learn CSS - [Layout](https://web.dev/learn/css/layout/)

Inline elements behave like words in a sentence. They sit next to each other in the inline direction. Elements such as `<span>` and `<strong>`, which are typically used to style pieces of text within containing elements like a `<p>` (paragraph), are inline by default. They also preserve surrounding whitespace. Height and width cannot be specified on an inline element. A block element will expand to the size of an inline element. The **display** element also determines how an element's children behave. **Flex** is used for one dimensional layouts, across a single axis, either horizontally or vertically. By default, flexbox will align the element's children next to each other, in the inline direction, and stretch them in the block direction, so they're all the same height. Use `flex-wrap` property to wrap text. **Grid** is used to control multi-axis layouts. fr is used as a fraction of the remaining space. Using inline-block gives you a box that has some of the characteristics of a block-level element, but still flows inline with the text. The **float** property instructs an element to "float" to the direction specified. A min width for lists can be specified using `column-width`. The **position** property changes how an element behaves in the normal flow of the document, and how it relates to other elements. The available options are relative, absolute, fixed and sticky with the default value being static.

### Duckett HTML/CSS book: Ch. 15, “Layout” (again; repeat of Class 4 reading)

Building Blocks: **block-level** box or an **inline** box, Block-level boxes start on a new line, are the main building blocks of a layout. Inline boxes flow between surrounding text.Use borders, margins, padding, and background colors to separate boxes. Control the positioning using relative, absolute, fixed, float (followed by defining top/bottom, left/right, width, etc.). Use z-index (stacking conent) to control which element sits on top. **Clear** can be used to say that no element will touch the left, right, both (or none) sides of a box. A fixed width layout uses pixels and a liquid layout uses percentages. Multiple style sheets can be used as an approach.`<div>` elements are often used as containing elements to group together sections of a page. Floated items require a defined width. Designers keep pages within 960 - 1000 pixels wide.
