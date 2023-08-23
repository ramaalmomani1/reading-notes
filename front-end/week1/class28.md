# Component Lifecycle / useEffect Hook

----

### useEffect hook

1. What is the main intended use case for the useEffect hook?

> Used to perform actions right after a component appears on the screen or when something in the component changes.


2. How does the effect’s logic interact with the component?

> The effects logic works with the component by running after the component renders. It handles tasks like getting data.

3. What is the importance of the return value from the effect’s logic function?

>  It's a way to make sure that when your component is no longer needed or changes, any extra things created by the effect are properly cleaned up.This keeps your app running smoothly.