# Read: 11 - Assorted Topics

via "HTML & CSS: Design and Build Websites" and "Javascript & JQuery: Interactive front-end web development" by Jon Duckett

## Chapter 16: “Images” (pp.406-427)

Controlling image dimensions can be defined via css using class names and indicating the width and height properties. Image sizes should be consistent throughout a site. The **Float** property can be used to move an element to the *left* or *right* of its containing bock, allowing text to flow around it. The float property is increasingly being used to align images. By default images are inline elements. To **center** an image, it should be turned into a **block level element** using the **display** property. On the containing element, use the **text-align** property with a value of **center** and set the margin property for left and right margins to **auto**.

**Background images** can be assigned to an entire page or just part of the page. A background image will repeat to fill the entire box by default`background-image: url('<URL>');`. Background images can be defined to repeat horizontally `repeat-x` or vertically `repeat-y` or only shown once `no-repeat`. Can also indicate if a background image is fixed or scroll and position of background `background-position` (left top, left center, left bottom, and so on). Images can be shown on hover and a single image can be used for several different parts of an interface, known as **sprinte**. Text must be low contrast in order to overlay text on a background image.

## Chapter 19: “Practical Information” (476-492)

***Search Engine Optimization (SEO)** is the practice of trying to help your site appear nearer to the top of search engine results when people look for the optics that your website cover. Getting sites to link to you is just as important as on-page techniques. Make sure to add relevant keywords in between the opening and closing `<a>` tag.

On-page SEO:

- **Page Title:** shown in the browser tab, specified in the `<title>` element
- **URL / Web address:**the name of the file is part of the URL, use keywords in the file name
- **Headings:** If keywords are in a heading element then a search engine will know that this page is all about that subject and will give it greater weight than other text.
- **Text:** repeat the keywords in the main body of the text.
- **Link Text:** Use keywords in the text that create links between pages
- **Image Alt Text:** Provide accurate descriptions of image in the alt text.
- **Page Descriptions:** Specify the description in the `<head>` element using a `<meta>` tax.

Use **Google Analytics** to analyze your size data, specifically: visits, unique visits, page views, pages per visit, average time on site, date selector, export data results, pages, landing pages, top exit pages, bounce rate, referrers, search terms. A domain name and hosting are needed to put a site on the web.

## [Video and Audio APIs](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Video_and_audio_APIs)

Part of the HTML5 spec, the HTMLMediaElement API provides features to allow you to control video and audio players programmatically...refer to the link to download a file to incorporate these controls for video and audio files.

## Chapter 9: Flash/Video/Audio (pp. 201-206)

Flash is no longer supported by many browsers but is an important part of history. Flash was once a popular tool for creating animations, but more and more people are switching to HTML5 for a number of reasons. Flash does not always meet accessibility requirements.
