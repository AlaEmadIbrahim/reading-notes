# Read: Class 26

## Component Based UI

1- React apps consist of components that form the UI. Components are units with logic and appearance, ranging from small elements like buttons to entire pages.

2- React components start with capitals, while HTML tags are lowercase.

3- JSX is JavaScript XML, stricter than HTML, used to embed markup into JavaScript code for UI representation.

4- Embed JavaScript expressions using curly braces in JSX, such as displaying variables or passing values to attributes.

5- React uses regular JavaScript techniques for iteration and conditional logic, like using if statements.

6- React responds to user input via event handlers declared within components.

7- Functions beginning with "use" are Hooks in React, like useState.

8- Sharing Data between Components: Components share data by lifting state up, updating state in a common parent component.

## Render and Commit

1- The steps involve triggering a render, rendering the component, and committing changes to the DOM.

2- Trigger updates post-initial render using createRoot and render methods.

3- React doesn't recreate DOM nodes on every rerender; it updates components based on state changes.

4- After updating the DOM, React applies minimal operations to match the latest rendering output for user visibility.
