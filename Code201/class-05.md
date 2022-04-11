# Read: 05 - HTML Images; CSS Color & Text

via "HTML & CSS: Design and Build Websites" and "Javascript & JQuery: Interactive front-end web development" by Jon Duckett

## Chapter 5: “Images” (pp.94-125)

Images should be relevant, convey information, convey the right mood, be instantly recognizable, and fit the color palate. It is best practice to create an img folder and have subfolders to store all images for your site. To add an image to your site, use the `<img>` element that carries the following attributes: src (image url), alt (text description), and title (additional info), height, width.

Three rules for creating images:

1. Save images in the right format
2. Save images at the right size
3. Measure images in pixels

Image formats: JPEG (preferred), GIF, PNG. The smaller the size, the quicker it is to load an imge on your site. Vector images are commonly created in Adobe Illustrator.

## Chapter 11: “Color” (pp.246-263)

- RGB Values: how much red, green, blue colors are used to make it up
- Hex Codes: 6 digit codes that represent the amount of red, green, blue in a color
- Color Names: 147 predefined colors
- HSLA: hue, saturation, and lightness
- HSL: hue, saturation, lightness, and alpha

Color details also include hue, saturation, lightness, and contrast. Opacity is used as well. It is important that there is enough contrast between text and background color.

## Chapter 12: “Text” (pp.264-299)

Typeface terminology: serif, sans-serif, monospace, weight, style, stretch, cursive, fantasy.

- **Font-family**: allows to specify the typeface that should be used
- **Font-size**: enables to specify a size for the font by pixels (px), percentages, and ems
- **Font-face**: allows to specify a font that isn't installed on the computer
- **Font-weight**: normal, bold
- **Font-style**: normal, italic, oblique
- **Text-transform**: uppercase, lowercase, capitalize
- **Text-decoration**: none, underline, overline, line-through, blink
- **Line-height**: sets the height of the entire line
- **Letter-spacing, word-spacing**: gap between words
- **Text-align:** left, right, center, justify
- **Vertical-align**: commonly used with img, strong, and em elements
- **Text-indent**: allows to indent the first line of text
- **Text-shadow:** creates a drop shadow
- **:first-letter, :first-line**
- **:link, :visited** - styling links
- **:hover, :activate, :focus** - responding to users using pseudo-classes

## Blog Post - JPEG vs PNG vs GIF

NOTE: The post has a TL;DR you might find handy. See [here](https://blog.imagekit.io/jpeg-vs-png-vs-gif-which-image-format-to-use-and-when-c8913ae3e01d).

- **JPEG** format: images that contain a natural scene or photograph where variation in color and intensity is smooth.
- **PNG** format: images that need transparency or images with text & objects with sharp contrast edges like logos.
- **GIF** format: containing animation
