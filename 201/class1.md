# Class 1 Notes

## Compose a short poem describing how HTTP sends data between computers.

- The browser sends an HTTP request message to the server, asking it to send a copy of the website to the client.

## Describe how HTML, CSS, and JS files are “parsed” in the browser.

- The browser parses the HTML file first, and that leads to the browser recognizing any 'link'-element references to external CSS stylesheets and any 'script' element references to scripts.
- As the browser parses the HTML, it sends requests back to the server for any CSS files it has found from 'link' elements, and any JavaScript files it has found from 'script' elements, and from those, then parses the CSS and JavaScript.
- The browser generates an in-memory DOM tree from the parsed HTML, generates an in-memory CSSOM structure from the parsed CSS, and compiles and executes the parsed JavaScript.

## How can you find images to add to a Website?

- Find something you own or have a resource that has free images.

## How do you create a String vs a Number in JavaScript?

- All text information in JavaScript is considered to be a string.
To create a string — just wrap any sequence of characters in quotes.
Quotes can be single, double or backtick.

- The important thing when it comes to both of them is how you save them. Numbers usually dont have quotes.

## What is a Variable and why are they important in JavaScript?

- A variable is like a bucket. You put something in the bucket and pull that something out later. They can contain just about anything but usually its numbers and strings.

## What is an HTML attribute?

- Attributes contain extra information about the element that won't appear in the content. In this example, the class attribute is an identifying name used to target the element with style information.

### An attribute should have:

- A space between it and the element name. (For an element with more than one attribute, the attributes should be separated by spaces too.)
The attribute name, followed by an equal sign.
An attribute value, wrapped with opening and closing quote marks.

## Describe the Anatomy of an HTMl element. 

- The opening tag: This consists of the name of the element (in this example, p for paragraph), wrapped in opening and closing angle brackets. This opening tag marks where the element begins or starts to take effect. In this example, it precedes the start of the paragraph text.
- The content: This is the content of the element. In this example, it is the paragraph text.
- The closing tag: This is the same as the opening tag, except that it includes a forward slash before the element name. This marks where the element ends. Failing to include a closing tag is a common beginner error that can produce peculiar results.

## What is the Difference between 'article' and 'section' element tags? 

- The HTML article element is used to wrap independent and self-contained content. The HTML section element is used to divide thematically defined pieces.

## What Elements does a “typical” website include?

- Header
- Nav Bar
- Main Content 
- Sidebar
- Footer

## How does metadata influence Search Engine Optimization?

- Metadata is data that describes data. Metadata tells search engines how to read and display sites on search engine result pages (SERPs). To optimize your metadata for search engines, you should focus on your website's title tag and meta descriptions.

## How is the 'meta' HTML tag used when specifying metadata?

- The 'meta' tag defines metadata about an HTML document. Metadata is data (information) about data. 'meta' tags always go inside the 'head' element, and are typically used to specify character set, page description, keywords, author of the document, and viewport settings.

## What is the first step to designing a Website?

- Define what you want to accomplish with it.

## What is the most important question to answer when designing a Website?

- What exactly do I want to accomplish?
- How will a website help me reach my goals?
- What needs to be done, and in what order, to reach my goals?

## Why should you use an 'h1' element over a 'span' element to display a top level heading?

- 'h1' gives the text it wraps around the role (or meaning) of "a top level heading on your page. where as 'span' will render it to look like a top level heading, but it has no semantic value.

## What are the benefits of using semantic tags in our HTML?

- Search engines will consider its contents as important keywords to influence the page's search rankings 
- Screen readers can use it as a signpost to help visually impaired users navigate a page
- Finding blocks of meaningful code is significantly easier than searching through endless divs with or without semantic or namespaced classes
- Suggests to the developer the type of data that will be populated
- Semantic naming mirrors proper custom element/component naming

## Describe 2 things that require JavaScript in the Browser?

- Adding interactive behavior and to connect servers to websites and web applications.

## How can you add JavaScript to an HTML document?

- With the 'script' element. Inline, external, and internal.

## Things i want to know more about

- More about metadata since there seems to be a lot there. 
- Why we chose to use inline javaScript durning the demo.
- Understanding more JS theory.