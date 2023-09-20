# Redux - Additional Topics

---- 

#### Redux Toolkit (RTK)

1. What concerns are addressed by Redux Toolkit?

> Redux Toolkit addresses concerns about Redux by simplifying Configuring a Redux store, reducing the need for multiple packages and minimizing boilerplate code.

2. What does configureStore() do?

> configureStore() simplifies Redux store setup by providing easy configuration options, combining reducers, adding middleware, and enabling Redux DevTools Extension.

3. How would I use createSlice()?

> To use createSlice(), provide reducers, a slice name, and an optional initial state. It generates a slice reducer, action creators, and types automatically, making Redux code shorter and simpler.

----

#### MobX

1. What is Mobx?

> MobX is a state management solution often used with React, known for simplicity and automatic state consistency.

2. How does MobX make it “impossible” to produce an inconsistent state?

> MobX ensures consistent state by automatically tracking and updating any value derived from the application state.

3. How would we build a reactive user interface?

> To build a reactive UI with MobX, make your data observable, create computed values, and use the observer wrapper for React components to ensure automatic updates.
