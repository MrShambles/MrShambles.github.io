# Code-201 Class 1 Reading

<details>
<summary>Compose a short poem describing how HTTP sends data between computers.</summary>

In realms of code, where data streams flow,
HTTP, the courier, starts its show.
Through digital veins, it swiftly flies,
Bridging the gap 'neath boundless skies.

From server's realm to client's domain,
It carries payloads, a digital train.
With packets small, in bytes they ride,
On pathways vast, they swiftly glide.

Through routers, switches, cables tight,
HTTP guides them in the night.
A protocol sure, in its design,
To link the distant, to intertwine.

It speaks in tongues, of requests and replies,
Of headers, bodies, where data lies.
A language clear, yet hidden deep,
In the cyber ether, it does seep.

And so it goes, this dance of bits,
HTTP, the connector, never quits.
In the world of bytes, it reigns supreme,
A conduit of dreams, in the digital stream.

</details>

<details>
<summary>Describe how HTML, CSS, and JS files are “parsed” in the browser.</summary>

### HTML Parsing:

- The browser starts by fetching the HTML file.
- It then parses the HTML document using a parser, which reads the document from top to bottom.
- The parser constructs a Document Object Model (DOM) tree, representing the structure of the HTML document.
- Elements, attributes, and their relationships are identified and organized within the DOM tree.
- As parsing proceeds, the browser starts fetching external resources referenced in the HTML, such as CSS and JavaScript files.

### CSS Parsing:

- Once an external CSS file is fetched, or if CSS is embedded within the HTML using < style > tags, the browser starts parsing the CSS.
- CSS rules are parsed and applied to the corresponding elements in the DOM tree.
- The browser constructs a CSS Object Model (CSSOM), which represents the styles defined in the CSS files.

### JavaScript Parsing:

- When the browser encounters a JavaScript file (either inline or external), it starts fetching and parsing it.
- JavaScript parsing is typically deferred until the HTML parsing is complete, especially when the script is placed at the end of the HTML document or marked with defer or async attributes.
- As JavaScript is parsed, the browser generates an Abstract Syntax Tree (AST) representing the structure of the script.
- Function and variable declarations are hoisted, and the script's execution context is set up.
- Event listeners, timers, and other asynchronous tasks defined in the JavaScript are registered for execution.

</details>

<details>
<summary>How can you find images to add to a Website?</summary>

### Decide on the Type of Image You Need

Determine the purpose of the image on your website. Is it a header image, a product photo, or an illustration? Knowing this will help you narrow down your search.

### Search for Free Stock Images Websites

 There are many websites that offer free stock images for you to use. Some popular ones include Unsplash, Pixabay, and Pexels. You can use these images for personal or commercial use without worrying about copyright.

### Explore the Image Library

 Once you've chosen a website, use its search bar to find images related to your topic. For example, if you're creating a website about nature, you might search for keywords like "nature", "landscape", or "trees".

### Download the Image

 When you find an image you like, click on it to view it in full size. Look for a download button or link nearby. Click on it to download the image to your computer.

### Include the Image in Your HTML Code

 Once you have downloaded the image, you can add it to your website using HTML. Use the < img > tag with the src attribute to specify the file path of the image on your computer.

##### Example Below:
 < img src="image.jpg" alt="Description of the image" >

 Replace "image.jpg" with the file path of the image you downloaded. Make sure the image file is in the same directory as your HTML file, or provide the correct path if it's located elsewhere on your computer.

 </details>

 <details>
 <summary>How do you create a String vs a Number in JavaScript?</summary>

 To create a string, you simply enclose your text within either single quotes (') or double quotes ("). Both methods are valid and produce the same result.

let myString1 = 'Hello, world!';
let myString2 = "Hello, world!";
Both myString1 and myString2 now contain the string "Hello, world!".

Creating a Number:
Creating a number in JavaScript is as simple as assigning a numeric value to a variable.

let myNumber = 42;

</details>

<details>
<summary>What is a Variable and why are they important in JavaScript?</summary>

### Data Storage
 Variables allow developers to store data such as numbers, strings, objects, arrays, and more. This data can then be accessed and manipulated throughout the program's execution.

### Dynamic Typing
JavaScript is a dynamically typed language, meaning variables can hold values of any data type, and the data type of a variable can change during runtime. This flexibility allows for more fluid and expressive coding.

### Data Manipulation
 Variables enable developers to manipulate data by performing operations such as arithmetic calculations, string concatenation, array manipulation, and more.

### Scope
Variables in JavaScript can have different scopes, which determine where they can be accessed in the code. Understanding and managing variable scope is crucial for writing maintainable and bug-free code.

### Reuse and Flexibility
 Variables allow developers to reuse values throughout their code, making it easier to write modular and maintainable programs. They also provide flexibility by allowing values to be assigned, updated, and reassigned as needed.

### Passing Values
 Variables play a key role in passing values between different parts of a program, such as functions, objects, and modules. They enable data to be shared and communicated between different components of the codebase.

 </details>

 <details>
 <summary>What is an HTML attribute?</summary>

In HTML, an attribute is a special piece of information added to a tag that provides additional details about the element or modifies its behavior. Attributes are specified within the start tag of an HTML element and are written as name-value pairs.

</details>

<details>
<summary>Describe the Anatomy of an HTMl element.</summary>

**The anatomy of an HTML element consists of several components that together define its structure and behavior within an HTML document. Here's a breakdown of the various parts**

### Start Tag
 This is the opening part of the element, denoted by the element's name enclosed in angle brackets (< and >). It marks the beginning of the element's presence in the document.

### Element Name
 Also known as the tag name, it identifies the type of element being used. Examples include < div >, < p >, < img >, < a >, etc.

### Attributes
 These are additional properties or settings that can be applied to the element. Attributes are specified within the start tag and are written as name-value pairs. Examples include href, src, id, class, etc.

### Attribute Value
 For each attribute, there is a corresponding value that provides specific information or instructions. Attribute values are typically enclosed in double quotes, although single quotes are also allowed.

### Content
 This is the inner part of the element where the actual content resides. Not all elements have content, but for those that do (e.g., < p >, < div >, < span >), it is placed between the start tag and the end tag.

### End Tag
 This is the closing part of the element, denoted by the element's name preceded by a forward slash (/) and enclosed in angle brackets (< and >). It marks the end of the element's presence in the document.

 </details>

 <details>
 <summary>What is the Difference between < article > and < section > element tags?</summary>

 the < article > element is used to represent independent, self-contained content, such as a blog post or a news article. On the other hand, the < section > element is used to group related content together, typically within a larger document.

 </details>

 <details>
 <summary>What Elements does a “typical” website include?</summary>

Some elements a typical website would have would be:

- Doctype
- html
- head
- title
- section
- footer

to make these elements work, you will add the <> around the element.

</details>

<details>
<summary>How does metadata influence Search Engine Optimization?</summary>

Metadata plays a crucial role in search engine optimization by providing information about a web page to search engines, which helps them understand and index the content more effectively. 

</details>

<details>
<summary>How is the < meta > HTML tag used when specifying metadata?</summary>

The < meta > HTML tag is used to specify metadata within the < head > section of an HTML document. Metadata provides additional information about the document, such as its character encoding, viewport settings, authorship, description, keywords, and more.

</details>

<details>
<summary>What is the first step to designing a Website?</summary>

Define what you want to accomplish with it.

</details>

<details>
<summary>What is the most important question to answer when designing a Website?</summary>

__What exactly do I want to accomplish?__

</details>

<details>
<summary>Why should you use an < h1 > element over a < span > element to display a top level heading?</summary>

Using an < h1 > element over a < span > element for a top-level heading provides semantic meaning and improves accessibility for users and search engines.

</details>

<details>
<summary>What are the benefits of using semantic tags in our HTML?</summary>

### Improved Accessibility
 Semantic tags provide meaning and structure to the content, making it easier for screen readers and other assistive technologies to interpret and navigate the web page.

### Enhanced SEO
 Search engines rely on semantic HTML to understand the content and context of web pages better. Using semantic tags can improve search engine visibility and rankings.

### Better Code Readability and Maintainability
 Semantic HTML makes the code more understandable and easier to maintain for developers and other team members.

### Future-proofing
 Semantic tags provide a standardized way to mark up content, ensuring compatibility with current and future web standards and technologies.

### Clarity and Consistency
 Semantic tags help developers and designers communicate the intended structure and purpose of different elements within the document, leading to more consistent and predictable rendering across browsers and devices.

### Separation of Structure and Presentation
 Semantic HTML encourages separating content structure from presentation, facilitating better styling and layout control through CSS.

</details>

<details>
<summary>Describe 2 things that require JavaScript in the Browser?</summary>

### Client-Side Form Validation
 JavaScript is commonly used to validate user input in web forms before submission, ensuring that data meets specified criteria such as required fields, correct format, and valid values.

### Dynamic Content Updates
 JavaScript allows for dynamic updates to web content without requiring a full page reload. This includes features such as interactive maps, live chat functionality, and real-time data updates in web applications.

 </details>

<details>
<summary>How can you add JavaScript to an HTML document?</summary>

You can add JavaScript to an HTML document by including < script > tags in the document's < head > or < body > section, or by linking to an external JavaScript file using the src attribute within the < script > tag.

</details>







