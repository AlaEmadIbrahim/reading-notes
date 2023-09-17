# Redux Toolkit (RTK)

The official, opinionated, batteries-included toolset for efficient Redux development

## Purpose
The Redux Toolkit package is intended to be the standard way to write Redux logic. It was originally created to help address three common concerns about Redux:

- "Configuring a Redux store is too complicated"

- "I have to add a lot of packages to get Redux to do anything useful"

- "Redux requires too much boilerplate code"

configureStore():

wraps createStore to provide simplified configuration options and good defaults. It can automatically combine your slice reducers, adds whatever Redux middleware you supply, includes redux-thunk by default, and enables use of the Redux DevTools Extension.

Slice:

accepts an object of reducer functions, a slice name, and an initial state value, and automatically generates a slice reducer with corresponding action creators and action types.

| Home Page               | [Home Page](./README.md)                                |
