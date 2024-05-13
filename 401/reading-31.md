# Reading-31


1. Summarize the five principles for structuring state.
The five principles for structuring state are: Single Source of Truth, State is Read Only, Changes are Made with Pure Functions, Changes are Made with Pure Functions, Changes are Made with Pure Functions, and Components are Stateless. These principles help in creating scalable, predictable, and maintainable state management systems in applications.

2. What problem do Contexts aim to solve?
Contexts aim to solve the problem of prop drilling, which is passing data through multiple levels of components explicitly via props. Contexts provide a way to share values like themes, user preferences, or any global data across the component tree without explicitly passing props at every level.

3. What is one technique to try before useContext?
Before using useContext, you can try the "prop drilling" technique. Prop drilling involves passing down props through multiple levels of components until they reach the component where they are needed. While it's a straightforward technique, it can lead to issues like code clutter and decreased readability as the application grows in complexity.

4. What hook complements useContext for complex applications?
The useReducer hook complements useContext for complex applications. While useContext provides a way to access the context value, useReducer is often used in conjunction with useContext to manage more complex state logic. It helps in managing state transitions in a predictable way, especially when the state logic involves multiple actions and complex data structures.

## Things I want to know more about
