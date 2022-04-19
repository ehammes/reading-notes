# Read: 12 - Docs for the HTML `<canvas>` Element & Chart.js

Read [this article](https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/) on the Chart.js API.[Chart.js docs](https://www.chartjs.org/docs/latest/): You’ll be needing these!

Chart.js, a Javascript plugin, can be used to make all sorts of charts for graphing data such as line, bar, pie, etc. Examples of these can be viewed [here](https://www.webdesignerdepot.com/cdn-origin/uploads7/easily-create-stunning-animated-charts-with-chart-js/chartjs-demo.html) and additional information can be located [here](https://www.chartjs.org/docs/latest/).

**Read the following articles on the Canvas API.**

- [Basic usage](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Basic_usage)
- [Drawing shapes with canvas](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes)
- [Applying styles and colors](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Applying_styles_and_colors)
- [Drawing text](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_text)

The Canvas element only has two properties: width, height - optional and can be configured via DOM properties. Fallback content can be defined in case of older browsers who do not support it. The Canvas element creates a fixed-size drawing surface that exposes one or more rendering contexts, which are used to create and manipulate the content shown. There are three functions that draw rectangles: `fillRect(x, y, width, height)` draws a filled rectangle, `strokeRect(x, y, width, height)` draws a rectangular outline, `clearRect(x, y, width, height)` clears the specified rectangular area, making it fully transparent. Functions to draw a path:

- `beginPath()`: creates a new path. Once created, future drawing commands are directed into the path and used to build the path up.
- `Path methods`:  Methods to set different paths for objects.
- `closePath()`: Adds a straight line to the path, going to the start of the current sub-path.
- `stroke()`: Draws the shape by stroking its outline.
- `fill()`: Draws a solid shape by filling the path's content area.

Steps to create paths: 1. call the `beginPath()` 2. calling the methods that actually specify the paths to be drawn and 3. call `closePath()`. Arcs, rectangles, curves, and combinations can be created too. The `Path2D()` constructor returns a newly instantiated Path2D object, optionally with another path as an argument (creates a copy), or optionally with a string consisting of **SVG path** data.

**fillStyle** and **strokeStyle** properties can be used to apply colors to a shape. There are many approaches that can be taken to apply colors that affect gradient, lines, transparency, patterns, and shadows. To draw text, the following methods are used:

- `fillText(text, x, y [, maxWidth])`: Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
- `strokeText(text, x, y [, maxWidth])`: Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.
