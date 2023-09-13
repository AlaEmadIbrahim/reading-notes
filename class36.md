# Redux

## What is the first principle of Redux?

- represent he whole state of the application as a single javascript object
- every thing changed in the application is contained in a single object.

## What is a store and what do we use our reducers for within that store?

A store is an immutable object tree in Redux. A store is a state container which holds the application’s state. Redux can have only a single store in your application. Whenever a store is created in Redux, you need to specify the reducer.

Let us see how we can create a store using the createStore method from Redux. One need to import the createStore package from the Redux library that supports the store creation process as shown below −

createStore reducer is a function that returns the next state of app. A preloadedState is an optional argument and is the initial state of your app. An enhancer is also an optional argument. It will help you enhance store with third-party capabilities.

A store has three important methods as given below −

- getState It helps you retrieve the current state of your Redux store.

- dispatch It allows you to dispatch an action to change a state in your application.

- subscribe It helps you register a callback that Redux store will call when an action has been dispatched. As soon as the Redux state has been updated, the view will re-render automatically.

Name three Redux store methods given to us by createStore and describe their use. Explain to a non-technical recruiter what combineReducers() does and why it is useful.

### Reducers:

are a pure function in Redux. Pure functions are predictable. Reducers are the only way to change states in Redux. It is the only place where you can write logic and calculations. Reducer function will accept the previous state of app and action being dispatched, calculate the next state and returns the new object.

| Home Page               | [Home Page](./README.md)                                |
