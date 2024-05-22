# Reading-37

### Why create multiple reducers?

Creating multiple reducers helps in managing different parts of the application's state separately, promoting modularity, maintainability, code reusability, and testability.

### How would you combine multiple reducers?

You combine multiple reducers using the `combineReducers` function provided by Redux, which takes an object where each key corresponds to a slice of the state and each value is the reducer function managing that slice.

### How will you manage state as an immutable object? Why?

Managing state as an immutable object ensures predictable state changes, traceability, and facilitates certain optimizations like shallow comparisons, improving performance. Immutable state management can be achieved using techniques like spreading objects in JavaScript or using libraries like Immutable.js.

### combineReducers is a utility function to simplify the most common use case when writing ___ _____ .

`combineReducers` is a utility function to simplify the most common use case when writing Redux reducers.

### Explain how combineReducers assembles the new state tree.

`combineReducers` assembles the new state tree by calling each reducer with its corresponding slice of state and the action, then combines the results into a single state object. Each slice of the state is updated only by its respective reducer.

### How would you define initial state in an app using combineReducers?

Initial state can be defined directly within each reducer function. Each reducer sets its own initial state when the state argument is `undefined`.

### Why will you want to split your reducing functions as your app becomes more complex?

Splitting reducing functions as the app becomes more complex helps in managing complexity, maintaining readability, and allows each reducer to focus on a specific aspect of the state, enhancing code organization and collaboration among developers.

### The _____ helper function turns an object whose values are different reducing functions into a single reducing function you can pass to ____.

The `combineReducers` helper function turns an object whose values are different reducing functions into a single reducing function you can pass to `createStore`.

### What is a popular convention when naming reducers?

A popular convention when naming reducers is to name them after the part of the state they manage, helping in quickly identifying the purpose of each reducer.

## Things I want to know more about