# reading-06 #

**How would you describe an object to a non-technical friend you grew up with?**
In JavaScript, think of an object like a digital version of your favorite childhood toy. It bundles together information (properties) and things you can do with it (methods). For example, a person object might have properties like name and age, and methods like walking or talking. It's a way to organize related details about something in your code.

**What are some advantages to creating object literals?**
Simplicity and Conciseness
Flexibility
Readability
Dynamic Properties

**How do objects differ from arrays?**
use objects when dealing with data that has named properties, and use arrays when working with ordered collections of similar items. Both are powerful and complement each other in different scenarios.

**Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.**
Bracket notation is useful when working with object properties dynamically or when the property names are not valid identifiers or are stored in variables.

**Evaluate the code below. What does the term this refer to and what is the advantage to using this?**

const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}

The term this in this context refers to the object on which the method is called, which is the dog object. The term this in this context refers to the object on which the method is called, which is the dog object.

**What is the DOM?**
The DOM, or Document Object Model, is a programming interface for web documents

**Briefly describe the relationship between the DOM and JavaScript.**
JavaScript and the DOM work hand-in-hand to create dynamic and interactive web pages, allowing developers to manipulate the structure and content of documents in response to various events and conditions.


## Things I want to know more about ##