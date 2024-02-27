# Reading-02 #

**Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?**
Render.

**What is the very first thing to happen in the lifecycle of React?**
Mounting phase.

**Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates**
Constructor --> Render --> componentDidMount --> React Updates --> componentWiilMount.

**What does componentDidMount do?**
`componentDidMount()` is a lifecycle method in React that executes immediately after a component is mounted into the DOM. It's used for tasks such as fetching data from APIs, setting up subscriptions to external data sources, performing DOM manipulations, and integrating with third-party libraries. This method ensures that these tasks are executed only after the component has been fully rendered and added to the DOM, making it a convenient hook for initializing components and managing side effects.

**What types of things can you pass in the props?**
You can pass various types of data in props, including strings, numbers, booleans, arrays, objects, functions, and React elements. Props are typically used to pass data from parent components to child components in a React application.

**What is the big difference between props and state?**
The key difference between props and state in React is that props are immutable and passed down from parent to child components, while state is mutable and managed within a component. Props are used to pass data from parent to child components, whereas state is used for managing component-specific data and triggering re-renders when the state changes.

**When do we re-render our application?**
In React, the application re-renders when there is a change in the component's state or props. React automatically detects changes in state or props and re-renders the components affected by those changes to reflect the updated data in the user interface.

**What are some examples of things that we could store in state?**
Some examples of things that can be stored in component state include user input (such as form data), UI state (like toggling a modal or dropdown), fetched data from APIs, timers/intervals, and any data that changes over time in response to user interactions or external events. Essentially, state is used to manage dynamic data specific to a component.

## Things I want to know more about