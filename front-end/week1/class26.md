# React Quick Start



1. What are the building blocks of a React app?

> Components

2. What is the difference between an HTML element and a React component?

> HTML elements are like the basic building blocks you use to create a static structure, while React components are like advanced building blocks that allow you to create dynamic and reusable parts of a webpage.

3. What is JSX and why do we use it?

> Stands for JavaScript XML, it's a syntax extension for JavaScript that allows you to write HTML-like code within your JavaScript code.

4. Describe the process of embedding JavaScript expressions in JSX.

> To embed JavaScript expressions in JSX, we use curly braces {}.

5. Does React or JSX have any special features for iteration or conditional logic?

> In React, there is no special syntax for writing conditions. We use the same techniques we use in regular JavaScript. Same for the loops 

6. How does React know to respond to a user’s inputs?

> By declaring event handler functions inside the components


7. What word indicates that a React component manages data with a Hook?

> Functions starting with 'use' are called Hooks.

8. How can two react components share data?

> Props and useState: props are for passing one-time data from parent to child, and useState helps both parent and child share data that can change.

----

### Render and Commit

1. What are the three steps of refreshing a React UI?

> Triggering, Rendering and Rendering


2. How do you trigger updates to a component after the initial render?

> By updating its state.


3. Does React recreate DOM nodes on every rerender?

> No, once the differences are identified, React figures out the minimal set of changes needed to update the actual DOM to match the new Virtual DOM. 


4. After React has updated the DOM, what still needs to happen before the user sees the change?

> Browser rendering