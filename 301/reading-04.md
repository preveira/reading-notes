# Reading-04 #

**What is a 'Controlled Component'?** 
A controlled component in React is a form element whose value is controlled by React state. This means that the value of the form element is managed by React state and updated by React in response to user input.

**Should we wait to store the users' responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why?**
Whether to store the user's responses from the form into state immediately or wait until they submit the form depends on the specific requirements of the application. If real-time validation or computation based on the user's input is needed, updating the state as soon as they enter the data might be preferable. Otherwise, if only the final result of the form submission is required and no real-time operations are needed, updating the state upon form submission can be more efficient.

**How do we target what the user is entering if we have an event handler on an input field?**
When there's an event handler on an input field in React, you can target what the user is entering by accessing the `value` property of the event object passed to the event handler function. This allows you to access and manipulate the user's input within the event handler function.

**Why would we use a ternary operator?**

Rewrite the following statement using a ternary statement:

if(x===y){
  console.log(true);
} else {
  console.log(false);
}

ternary refactor:
console.log(x === y ? true : false);


## Things I want to know more about ##