# Redux - Combined Reducers

----

#### Multiple Reducers Example

1. Why create multiple reducers?

> * Modularity: Multiple reducers break down the state into manageable parts.
> * Scalability: Easier to add new features or state slices.
>* Reusability: Reducers can be reused across the application.

2. How would you combine multiple reducers?

> combineReducers

3. How will you manage state as an immutable object? why?

> * Predictable Updates: Immutable state ensures predictability.
> * Pure Functions: Redux reducers must be pure, not mutating state.
> * Time-Travel Debugging: Facilitates debugging by tracking state changes.
> * Performance: Immutable data structures optimize rendering.

---

#### Redux Docs: Using Combined Reducers

1. combineReducers is a utility function to simplify the most common use case when writing ___ _____ .

> Redux reducers
2. Explain how combineReducers assembles the new state tree.

> combineReducers puts together the new data structure (state) by using smaller functions (reducers) that each handle a specific part of the data. When an action happens, these smaller functions work together to update their respective parts of the data, and then the parts are combined into the new data structure.


3. How would you define initial state in an app using combineReducers?

> by providing a preloadedState when creating the store using createStore. Second, reducers can specify their initial state by checking if the incoming state is undefined and returning a default value. If preloadedState is provided, it overrides the initial state defined in reducers. If not, the reducer's default initial state is used.

----

#### Redux Docs: Combined Reducer Syntax

1. Why will you want to split your reducing functions as your app becomes more complex?

> To simplifies code, and eases collaboration and debugging.

2. The _____ helper function turns an object whose values are different reducing functions into a single reducing function you can pass to ____.

> combineReducers,  createStore.

3. What is a popular convention when naming reducers?

>  A common practice is to name reducers after the state slices they handle. For instance, if you manage "counter" and "todos" slices, simply use shorthand notation like counter and todos when combining them, enhancing code clarity and brevity.