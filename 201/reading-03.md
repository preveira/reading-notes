# Reading-03 #

**When should you use an unordered list in your HTML document?**
When you want to create a list with bullets

**How do you change the bullet style of unordered list items?**
You can use the list-style-type property

**When should you use an ordered list vs an unorder list in your HTML document?**
When you want to have a numbered list like 1,2,3,4,5 you use an ordered list, if you dont need the numbers and just need a bulleted list then you can use an unordered list.

**Describe two ways you can change the numbers on list items provided by an ordered list?**
You can use the list-style-type property in CSS and select upper-roman;
You can also use the type attrinute within the ordered list like such: <ol type="A"> which will use A,B,C letters instead of numbers

**Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?**
Margin represents the space outside the box. Like the Kingdoms guard out side the castle.
Padding represents the space within the box. Like the space inside the castle walls that comfortably pads the elements within.

**List and describe the four parts of an HTML elements box as referred to by the box model.**
Content:
The innermost part of the box is the content area. It holds the actual content of the element, such as text, images, or other nested elements. The size of the content area is determined by the width and height properties.

Padding:
Surrounding the content area is the padding. Padding is the space between the content and the element's border. It provides internal spacing and contributes to the overall size of the box. Padding can be adjusted using the padding property.

Border:
The border is the next layer, surrounding the padding. It marks the boundary of the element and separates the content from the surrounding elements. The border can be styled, and its width, style, and color can be controlled using the border property.

Margin:
The outermost layer is the margin. Margins create space between the border of the element and its neighboring elements. They ensure that elements do not get too close to each other, providing external spacing. The margin property is used to control the size of the margin.

**What data types can you store inside of an Array?**
Primitive Data Types:
Integer: Whole numbers (e.g., 1, -5, 42).
Float or Double: Decimal numbers (e.g., 3.14, -0.5, 2.0).
Character: Single characters (e.g., 'a', 'B', '1').
Boolean: True or false values.

Composite Data Types:
String: A sequence of characters (e.g., "hello", "world").
Object: Instances of user-defined classes or built-in objects.
Arrays: Arrays can be nested within other arrays, creating multidimensional arrays.

Mixed Data Types:
Some programming languages allow arrays to store elements of different data types within the same array. These are often referred to as heterogeneous arrays.

**Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?**
Yes, the people array you provided is a valid JavaScript array. It is a multidimensional array where each element is an array containing information about a person. To access the values stored in this array, you can use array indexing.

**Read the code below and evaluate the last expression and explain what the result would be and why.**

 **let a = 10;**
 **let b = 'dog';**
 **let c = false;**

 **// evaluate this**
 **(a + c) + b;**

a + c) is evaluated first, and since a is a number (10) and c is a boolean (false), JavaScript performs type coercion to convert the boolean to a number. In this case, false is treated as 0 in numerical operations.

So, (a + c) becomes 10 + 0, which equals 10. Then, the result (10) is concatenated with the string b using the + operator. Since one of the operands is a string, JavaScript performs string concatenation.

Therefore, the final result would be the string '10dog'.

**Describe a real world example of when a conditional statement should be used in a JavaScript program.**
A real-world example of when a conditional statement should be used in a JavaScript program is in a weather application that provides recommendations based on the current weather conditions.

**Give an example of when a Loop is useful in JavaScript.**
WHen you want to help reduce redundancy in code by automating repetitive tasks, making it easier to manage and process collections of data.


 ## Things I want to know more about ##