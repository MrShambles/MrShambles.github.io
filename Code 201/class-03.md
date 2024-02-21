# HTML Lists, Control Flow with JS, and the CSS Box Model

<details>
<summary>When should you use an unordered list in your HTML document?</summary>


You should use an unordered list ( <ul> ) in your HTML document when you want to represent a collection of items that do not have a specific order or sequence. Unordered lists are typically used when the order of the items is not important.

</details>

<details>
<summary>How do you change the bullet style of unordered list items?</summary>

You can change the bullet style of unordered list items using CSS. CSS allows you to customize the appearance of bullets (or markers) using the list-style-type property. 

</details>

<details>
<summary>When should you use an ordered list vs an unorder list in your HTML document?</summary>


Use an ordered list (< ol >) when the sequence or order of items matters, and use an unordered list (<ul>) when the order of items is irrelevant.

</details>

<details>
<summary>Describe two ways you can change the numbers on list items provided by an ordered list?</summary>

### Changing the list-style-type
 You can change the appearance of the numbers by using CSS and the list-style-type property. Common values include decimal, lower-roman, upper-roman, lower-alpha, and upper-alpha.

### Customizing the starting number
You can specify the starting number for the ordered list using the start attribute on the < ol > element. This allows you to begin the numbering at a specific value rather than the default value of 1.

</details>

<details>
<summary>Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?</summary>


In the whimsical tale of "The Box Model," Margin and Padding are characters with distinct personalities and roles to play.

Margin, the Friendly Boundary:
Margin is depicted as a courteous character, always standing at the outer edges of the scene, providing space and breathing room for everyone else. With a generous demeanor, Margin ensures that there's ample distance between elements, preventing them from feeling cramped or claustrophobic. Whenever new elements arrive on the scene, Margin greets them warmly, offering a bit of space to settle in comfortably. Despite being somewhat reserved, Margin's presence is essential for maintaining harmony and balance in the story.

Padding, the Supportive Cushion:
Padding is portrayed as the dependable companion who stands by the elements, offering them support and protection from external pressures. With a soft and nurturing nature, Padding wraps around each element like a cozy blanket, shielding them from the harsh realities outside. Whenever elements need a bit of extra comfort or security, Padding is there to lend a helping hand, ensuring that they feel safe and cared for. Although Padding may go unnoticed at times, its presence is crucial for keeping elements cozy and content within the confines of the story.

Together, Margin and Padding form an integral part of the Box Model's narrative, providing space, support, and structure to the elements within. Their roles may seem subtle, but without them, the story would feel cramped and chaotic, lacking the breathing room and comfort that make it truly enchanting.

</details>

<details>
<summary>List and describe the four parts of an HTML elements box as referred to by the box model.</summary>

### Content
 This is the innermost part of the box, where the actual content of the element, such as text, images, or other media, resides. The size of the content area is determined by the width and height properties.

### Padding
 Padding is the space between the content area and the element's border. It provides cushioning or breathing room around the content, separating it from the border. Padding can be set using the padding property in CSS.

### Border
 The border surrounds the padding and content areas, forming a visible boundary for the element. Borders can be styled with different thicknesses, colors, and styles using CSS properties such as border-width, border-color, and border-style.

### Margin
 Margins are the space outside the border of the element, creating distance between the element and other nearby elements. Margins are used to control the layout and spacing between elements on the page. They can be set using the margin property in CSS.

 </details>

 <details>
 <summary>What data types can you store inside of an Array?</summary>

 
Arrays in most programming languages can store various data types, including:

### Numbers (Integers, Floats, Doubles)
 Arrays can store numerical values of different types, such as integers (whole numbers), floats (decimal numbers), and doubles (double-precision floating-point numbers).

### Strings
 Arrays can store sequences of characters, commonly known as strings. Strings can represent text, words, or any combination of characters.

### Boolean Values
 Arrays can store boolean values, which represent true or false conditions. Boolean arrays are often used to store the results of logical operations or to control program flow.

### Objects
 Arrays can store references to objects, which are instances of user-defined or built-in classes. Objects can encapsulate data and behavior, allowing for more complex data structures within arrays.

### Other Arrays
 Arrays can store references to other arrays, enabling the creation of multidimensional arrays or arrays of arrays. This allows for the representation of more complex data structures, such as matrices or lists of lists.

### Mixed Data Types (In Some Languages)
 Some programming languages allow arrays to store elements of different data types within the same array. This feature is known as heterogeneity and is useful for creating versatile data structures.

In summary, arrays can store a wide range of data types, including numbers, strings, boolean values, objects, other arrays, and even mixed data types in some programming languages. This versatility makes arrays a fundamental and powerful tool for organizing and manipulating data in programming.

</details>

<details>
<summary>Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?</summary>

Yes, the people array is a valid JavaScript array. To access the values stored in the array, you can use array indexing and nested array indexing to access specific elements or properties within each nested array.

</details>

<details>
<summary>List five shorthand operators for assignment in javascript and describe what they do.</summary>

### +=
 This operator adds the value on the right side to the variable on the left side and assigns the result back to the variable.

### -=
This operator subtracts the value on the right side from the variable on the left side and assigns the result back to the variable.

### *=
This operator multiplies the variable on the left side by the value on the right side and assigns the result back to the variable.

### /=
This operator divides the variable on the left side by the value on the right side and assigns the result back to the variable.

### %=
This operator calculates the remainder of dividing the variable on the left side by the value on the right side and assigns the result back to the variable.

</details>

<details>
<summary>
Read the code below and evaluate the last expression and explain what the result would be and why.</summary>


In the provided code, the expression (a + c) + b; is evaluated. Let's break it down:

### a + c:
 In this part, a is a number (10) and c is a boolean value (false). JavaScript automatically converts the boolean value false to a number when performing arithmetic operations, where false is considered as 0. So, a + c evaluates to 10 + 0, which equals 10.

### 10 + b:
 Here, 10 is a number and b is a string ('dog'). When JavaScript encounters the + operator with a string operand, it performs string concatenation. Therefore, 10 + 'dog' results in the string '10dog'.

So, the result of the expression (a + c) + b; would be '10dog'. The numerical value 10 is converted to a string and concatenated with the string 'dog', resulting in the final string '10dog'.

</details>

<details>
<summary>Describe a real world example of when a conditional statement should be used in a JavaScript program.</summary>


A real-world example of when a conditional statement should be used in a JavaScript program is when building a website with a login system. You can use a conditional statement to check if the user has entered the correct username and password. If the credentials match those stored in the database, the user is granted access to the website; otherwise, they are denied access and prompted to try again or retrieve their login information. This helps ensure that only authorized users can access the website's protected content.

</details>

<details>
<summary>Give an example of when a Loop is useful in JavaScript.</summary>


A loop is useful in JavaScript when you need to perform a repetitive task, such as iterating over an array to process each element individually, calculating a series of values, or executing a block of code multiple times based on a certain condition. For example, you might use a loop to display a list of items on a webpage, process user input from a form, or perform calculations for generating a report.

</details>