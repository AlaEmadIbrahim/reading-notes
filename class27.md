# useState() Hook

## Thinking in React

Summarize the five steps of thinking in react.

- Building a static version of the UI using props and reusable components, identifying the minimal UI state needed, determining where the state should reside in the component hierarchy, and implementing inverse data flow to update the state based on user input.

## State: A Component’s Memory

What is one reason a local variable isn’t sufficient for managing a React component?

- It wouldn't trigger re-renders or allow access to React component lifecycle.

What is the argument to the useState hook, and what are the two parts of its return array?

- Its return array are the current state value and a function to update that state.

How can Component A access state from Component B?

- By passing down the state value as a prop from Component B to Component A.