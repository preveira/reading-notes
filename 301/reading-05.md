# Reading-05 #

**Single Responsibility Principle (SRP)**:
   The Single Responsibility Principle is a design principle in software development that states that a class or module should have only one reason to change. Applied to components, it means that each component should have only one responsibility or concern, and it should encapsulate that responsibility entirely. This principle helps in making components more modular, easier to understand, and maintainable.

**Building a 'static' version of your application**:
   Building a 'static' version of an application involves creating a version where data is hardcoded or preloaded rather than being fetched dynamically from a server or database. This static version typically represents the structure and layout of the application without the functionality of dynamic data manipulation.

**Adding functionality to a static application**:
   After creating a static version of an application, you need to add dynamic functionality. This involves integrating features such as user interactions, data fetching from servers, state management, and updating the UI in response to user actions.

**Three questions to determine state**:
   - Does it change over time?
   - Can it be derived from other state or props?
   - Does it need to be passed down from a parent component?

**Identifying where state needs to live**:
   State needs to live in the component where it's used and where it influences the rendering and behavior of that component. If multiple components need access to the same state or if the state needs to be shared across components, it should be lifted to the nearest common ancestor of those components.

**Higher-order function**:
   A higher-order function is a function that either takes one or more functions as arguments or returns a function as its result. It enables functions to be treated as first-class citizens, allowing for more flexible and powerful programming paradigms like functional programming.

**Exploring the `greaterThan` function**:
   Line 2 of the `greaterThan` function is performing a comparison between `m` and `n`. It checks if `m` is greater than `n` and returns `true` if the condition is satisfied, otherwise returns `false`.

**Map or reduce with higher-order functions**:
   Both `map` and `reduce` are higher-order functions commonly used in functional programming. 
   - `Map`: It applies a function to each element of a list and returns a new list with the results of applying the function to each element. For example, `map` can be used to transform an array of numbers by doubling each element.
   - `Reduce`: It applies a function against an accumulator and each element in the list (from left to right) to reduce it to a single value. It can be used to perform operations like summing up all elements in an array or finding the maximum value.


## Things I want to know more about