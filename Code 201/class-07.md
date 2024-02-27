# Object-Oriented Programming, HTML Tables

<details>
<summary>Explain why we need domain modeling.</summary>

Domain modeling is essential because it helps us understand the structure, relationships, and behavior of the entities within a specific area or domain. It provides a clear representation of the problem space, enabling effective communication between stakeholders, developers, and designers. This clarity ensures that software solutions are accurately aligned with the needs and requirements of the domain, leading to better-designed, more maintainable, and scalable systems.

</details>

<details>
<summary>Why should tables not be used for page layouts?</summary>

Tables should not be used for page layouts because they are designed for tabular data, not for structuring the layout of a webpage. Here are some reasons why:

### Semantic Meaning
 Tables are meant to display data in a structured format, such as rows and columns. Using tables for layout purposes violates the semantic meaning of HTML elements, making it harder for search engines and assistive technologies to interpret and understand the content.

### Accessibility
 Screen readers and other assistive technologies rely on the proper semantic structure of HTML to interpret web content for users with disabilities. Using tables for layout can create confusion and accessibility barriers for these users.

### Responsive Design
 Tables are not inherently responsive to different screen sizes and devices. Using CSS for layout allows for more flexible and responsive design, adapting to various screen sizes and orientations.

### Maintenance
 Using tables for layout can make the code more complex and difficult to maintain. CSS provides a cleaner separation between content and presentation, making it easier to update and modify the layout without changing the underlying structure of the HTML.

### Performance
 Tables for layout can lead to slower page loading times, especially for complex layouts with nested tables. CSS-based layouts are generally more lightweight and efficient in terms of performance.

 </details>

 <details>
 <summary>List and describe 3 different semantic HTML elements used in an HTML < table >.</summary>

 ### < caption >: 
 This element is used to provide a title or caption for the table. It typically appears above or below the table and helps provide context or summarize the purpose of the table.

### < thead >
 The < thead > element is used to group the header rows in a table. It typically contains one or more < tr > (table row) elements that represent the column headers of the table.

### < tbody >
 The < tbody > element is used to group the body content of the table. It contains one or more < tr > elements that represent the rows of data in the table.

 </details>

 <details>
 <summary>What is a constructor and what are some advantages to using it?</summary>

 ### Initialization
  Constructors allow you to set initial values for object properties or perform any necessary setup when creating an instance of a class.

### Encapsulation
 Constructors can enforce encapsulation by ensuring that an object is initialized properly before it can be used, helping to maintain the integrity of the object's state.

### Code Reusability
 By encapsulating initialization logic within a constructor, you can easily reuse it whenever you create new instances of the class.

### Clarity and Readability
 Using constructors makes your code more readable and self-explanatory, as it clearly indicates the initialization process for objects of a class.

### Consistency
 Constructors help ensure that objects are created in a consistent manner, reducing the likelihood of errors or unexpected behavior.

</details>

<details>
<summary>Explain prototypes and inheritance via an analogy from your previous work experience.</summary>

Imagine you're tasked with maintaining a fleet of aircraft, each with its own unique set of features and capabilities. Now, let's consider the concept of prototypes and inheritance:

### Prototypes 
In the context of aircraft maintenance, you can think of a prototype as a blueprint or a standard model of an aircraft. This prototype defines the common characteristics and behaviors shared among all aircraft in the fleet. For example, it may include specifications for engine types, fuel capacity, weight distribution, and maintenance procedures.

### Inheritance
 Inheritance in JavaScript is akin to inheriting features and functionalities from a prototype or standard model. Similarly, in aircraft maintenance, when you need to introduce a new type of aircraft to the fleet, you can base its design and functionality on an existing prototype. This new aircraft inherits certain attributes and behaviors from its prototype, such as engine specifications, fuel efficiency, and maintenance protocols.

 </details>
