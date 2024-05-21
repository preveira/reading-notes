# Reading-36

### What is the first principle of Redux?
The first principle of Redux is that the state of your whole application is stored in a single JavaScript object called the "store." This means the entire state tree of an application is kept in one place, making it easier to manage and debug.

### What is a store and what do we use our reducers for within that store?
A store is a central place where the state of your application is stored. It holds the application state and provides methods to access the state, dispatch actions, and register listeners. Reducers are functions used within the store to specify how the application's state changes in response to actions. When an action is dispatched, the store sends it to the reducer, which then determines how to update the state based on the action type and payload.

### Name three Redux store methods given to us by createStore and describe their use.
1. **getState()**: This method retrieves the current state of the application from the store. It is useful for accessing the state to read data or for debugging purposes.
2. **dispatch(action)**: This method sends an action to the store. The action describes what happened in the application, and the store will then pass this action to the reducer to update the state accordingly.
3. **subscribe(listener)**: This method registers a callback function that the store will call whenever an action has been dispatched and the state has potentially changed. It is used to update the UI or trigger other changes in response to state updates.

### Explain to a non-technical recruiter what combineReducers() does and why it is useful.
CombineReducers is a function in Redux that allows you to split the state management logic into separate functions, called reducers, that each manage a portion of the state. Instead of writing one large reducer to handle all state updates, combineReducers lets you write smaller, specialized reducers that handle specific parts of the state. This is useful because it makes the code easier to understand, maintain, and test by breaking it into more manageable pieces. For example, in a shopping cart application, one reducer might handle user information, another might handle the items in the cart, and yet another might manage the product catalog. CombineReducers combines these smaller reducers into a single reducing function you can pass to createStore, enabling a modular and scalable approach to state management.

## Things I want to know more about
