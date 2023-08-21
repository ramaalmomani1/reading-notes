# useState() Hook

---

#### Thinking in React

Summarize the five steps of thinking in react.

> **1. Break the UI into a component hierarchy:** Separate UI into components and subcomponent and naming them then  arrange them into a hierarchy

> **2. Build a static version in React:**  To build a version that renders the UI from your data model without adding any interactivity

> **3. Find the minimal but complete representation of UI state:** Figure out the absolute minimal representation of the state your application needs.

>**4. Identify where your state should live:**  Identify which component is responsible for changing this state, or owns the state. 

> **5. Add inverse data flow:** Passing functions from higher-level components to lower-level ones so that the lower-level components can trigger updates in the higher-level state when users interact with form elements.


---


#### State: A Component’s Memory

1. What is one reason a local variable isn’t sufficient for managing a React component?

>Local variables don’t persist between renders and changes to local variables won’t trigger renders. 


2. What is the argument to the useState hook, and what are the two parts of its return array?

> * A state variable to retain the data between renders.
>* A state setter function to update the variable and trigger React to render the component again.


3. How can Component A access state from Component B?

>Props which is a way of passing data from parent to child.