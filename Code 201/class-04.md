# HTML Links, JS Functions, and Intro to CSS Layout

<details>
<summary>To create a basic link, we wrap text or other content inside what element?</summary>

< a href="https://example.com">Click here to visit Example.com< /a >

</details>

<details>
<summary>
The href attribute contains what information?</summary>

The href attribute in HTML stands for "Hypertext Reference." It contains the URL (Uniform Resource Locator) or the address of the resource that the link points to. In simpler terms, it specifies the destination of the link.

</details>

<details>
<summary>What are some ways we can ensure links on our pages are accessible to all readers?</summary>


## Use Descriptive Link Text
 Make sure the text within the < a > element describes the purpose or destination of the link. Avoid generic text like "click here" or "read more." Instead, use descriptive phrases that convey the context of the link.

## Title Attribute
 Although not as commonly used as before, the title attribute can provide additional information about the link when users hover over it. However, it's essential not to rely solely on the title attribute for conveying crucial information, as it may not be accessible to all users, especially those using assistive technologies.

## Provide Context
 Ensure that the surrounding content provides context for the link. This could involve including introductory text or headings that help users understand the purpose of the link.

 </details>

 <details>
 <summary>What is meant by “normal flow”?</summary>

 In web design and layout, "normal flow" refers to the default positioning and arrangement of elements on a web page as dictated by the HTML and CSS specifications, without any additional positioning or layout adjustments applied.

 </details>

 <details>
 <summary>What are a few differences between block-level and inline elements?</summary>

 Block-level and inline elements are two types of HTML elements with different behaviors and characteristics. Here are a few key differences between them:

## Display Behavior

Block-level elements typically start on a new line and take up the full width available in their containing element.
Inline elements, on the other hand, do not start on a new line and only take up as much width as necessary. They flow within the text or content of a block-level element.

## Width and Height

Block-level elements have a default width of 100% of their containing element's width, and their height is determined by the content they contain or by explicitly setting a height.
Inline elements only occupy the width necessary to contain their content. They cannot have width or height applied to them directly.

## Allowed Content

Block-level elements can contain other block-level elements and inline elements.
Inline elements cannot contain block-level elements; they can only contain other inline elements or text.

</details>

<details>
<summary>___ positioning is the default for every html element.</summary>

Static positioning is the default for every HTML element.

</details>

<details>
<summary>Name a few advantages to using absolute positioning on an element.</summary>


Using absolute positioning on an element can offer several advantages, depending on the specific requirements of your design. Here are a few advantages:

## Precise Placement
 Absolute positioning allows you to precisely position an element relative to its nearest positioned ancestor. This level of control is useful for creating pixel-perfect layouts or overlaying elements exactly where you want them on the page.

## Layering and Overlapping
 Absolute positioning allows elements to overlap one another, creating visually interesting effects or layering elements on top of each other. This is particularly useful for creating overlays, tooltips, dropdown menus, or modal dialogs.

## Removal from Document Flow
 Absolutely positioned elements are removed from the normal document flow, meaning they don't affect the layout of surrounding elements. This can be advantageous for creating complex layouts where certain elements need to be positioned independently of others.

 </details>

 <details>
 <summary>What is a key difference between fixed positioning and absolute positioning?</summary>

## Absolute Positioning
When an element is absolutely positioned, it is positioned relative to its nearest positioned ancestor (an ancestor element with a position value other than static, such as relative, absolute, or fixed).
If no positioned ancestor is found, the element is positioned relative to the initial containing block, usually the < html > element.

## Fixed Positioning
Fixed positioning positions an element relative to the viewport, meaning it remains fixed in its position even when the user scrolls the page.
Fixed positioning does not depend on any ancestor elements; the element is always positioned relative to the viewport.

</details>

<details>
<summary>Describe the difference between a function declaration and a function invocation.</summary>

A function declaration defines a function, stating what the function does. A function invocation calls the function, executing its code.

</details>

<details>
<summary>What is the difference between a parameter and an argument?</summary>


A parameter is a variable in a function definition, while an argument is the actual value passed to a function when it is called. Parameters are used to define the inputs a function expects, while arguments are the specific values provided to those parameters when the function is invoked.

</details>

<details>
<summary>Pick 2 benefits to pair programming and reflect on how these benefits could help you on your coding journey.</summary>

## Improved Code Quality
 With two sets of eyes on the code, pair programming can lead to higher-quality code. The process involves continuous code review and discussion, which can catch bugs and errors early, leading to more robust solutions.

## How it could help me
 Pair programming would provide an opportunity to learn from my partner's expertise, catch mistakes more quickly, and improve my coding skills by receiving immediate feedback.

## Knowledge Sharing and Collaboration
 Pair programming encourages collaboration and knowledge sharing between team members. Each person brings their unique skills, experiences, and perspectives to the table, leading to better problem-solving and innovative solutions.

## How it could help me
 Pairing with other experts in the field of programming could help me gain insights into different approaches, learn about new techniques, and ultimately improve my capabilities.

</details>