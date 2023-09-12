# Application State with Redux

---

1. What is the first principle of Redux?

> Redux follows the principle of having a single, immutable state tree, meaning all of an application's data is stored in one object that can't be changed directly.

2. what is a store and what do we use our reducers for within that store?

> Redux follows the principle of having a single, immutable state tree, meaning all of an application's data is stored in one object that can't be changed directly.


3. Name three Redux store methods given to us by createStore and describe their use.

> * getState(): Gets the current application state.
> * dispatch(action): Dispatches actions to update the state.
> * subscribe(listener): Registers a listener to be notified of state changes.

4. Explain to a non-technical recruiter what combineReducers() does and why it is useful.

> Redux function used to combine multiple reducers into one. It's useful for managing complex state by breaking it into smaller, independent parts. This helps organize code and maintainability in large applications.