# Reading-03 #

**What does .map() return?**
The .map() function in JavaScript returns a new array populated with the results of calling a provided function on every element in the calling array.

**If I want to loop through an array and display each value in JSX, how do I do that in React?**
You can use the .map() function inside curly braces {} in JSX to iterate through an array and display each value.

**Each list item needs a unique ____.**
Each list item in React needs a unique key prop.

**What is the purpose of a key?**
The purpose of a key in React is to help React identify which items have changed, are added, or are removed. It helps optimize the rendering process by providing a stable identity to elements, especially when dealing with lists.

*What is the spread operator?**
The spread operator (...) is a syntax in JavaScript used for expanding elements of an iterable (like arrays, objects, strings) into places where multiple elements are expected.

**List 4 things that the spread operator can do.**

- Combine arrays
- Copy arrays
- Merge objects
- Pass elements of an iterable as function arguments

**Give an example of using the spread operator to combine two arrays.**
const array1 = [1, 2, 3];
const array2 = [4, 5, 6];
const combinedArray = [...array1, ...array2];
console.log(combinedArray);

**Give an example of using the spread operator to combine two objects into one.**
const oldArray = [1, 2, 3];
const newItem = 4;
const newArray = [...oldArray, newItem];
console.log(newArray);

**Give an example of using the spread operator to combine two objects into one.**
const obj1 = { a: 1, b: 2 };
const obj2 = { c: 3, d: 4 };
const combinedObj = { ...obj1, ...obj2 };
console.log(combinedObj); 

**what is the first step that the developer does to pass functions between components?**
They defined the function in the parent component

**In your own words, what does the handleClick function do?**
The handleClick function is like a special action button in React. It's a function that runs when something specific happens, like when you click on something in the app. Its job is to decide what should happen next after that click.

**How can you pass a method from a parent component into a child component?**
You can pass a method from a parent component to a child component by defining the method in the parent component and then passing it down to the child component as a prop. This allows the child component to access and invoke the method.

**How does the child component invoke a method that was passed to it from a parent component?**
The child component can invoke a method that was passed to it from a parent component by simply calling the method as a function within the child component. Since the method is passed as a prop, it is accessible within the child component, and invoking it will execute the function defined in the parent component.

## Things I want to know more about ##