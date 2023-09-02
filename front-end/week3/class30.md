# Context API

### Choosing the State Structure

1. Summarize the five principles for structuring state.

> * **Group related state**. If you always update two or more state variables at the same time, consider merging them into a single state variable.
> * **Avoid contradictions in state**. When the state is structured in a way that several pieces of state may contradict and “disagree” with each other, you leave room for mistakes. Try to avoid this.
> * **Avoid redundant state**. If you can calculate some information from the component’s props or its existing state variables during rendering, you should not put that information into that component’s state.
> * **Avoid duplication in state**. When the same data is duplicated between multiple state variables, or within nested objects, it is difficult to keep them in sync. Reduce duplication when you can.
> * **Avoid deeply nested state**. Deeply hierarchical state is not very convenient to update. When possible, prefer to structure state in a flat way.

---

### Passing State Deeply with Context

1. What problem do Contexts aim to solve?

> Contexts in React make it easy to share data between components, even if they are deep within the component tree, without the need for passing data through many components or making your code overly complicated.

2. What is one technique to try before useContext?

> prop drilling (pass data from a parent component down to deeply nested child components without using context)

3. What hook complements useContext for complex applications?

> useReducer hook
