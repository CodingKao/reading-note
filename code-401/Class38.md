# Class 38: Reading: Redux - Asynchronous Actions

#### Link to article: [async actions](https://redux.js.org/tutorials/fundamentals/part-6-async-logic)

#### Link to article: [thunk middleware](https://github.com/reduxjs/redux-thunk)


***

**Bookmarks**


***

## async actions

**Why use Redux middleware?**
> Redux middleware is used to enable writing logic with side effects, such as making AJAX calls, modifying function arguments, or generating random values. It allows us to handle async operations and interact with the Redux store by dispatching actions after the async operations have completed.

**Consider the Redux Async Data Flow Diagram. Describe the flow in your own words.**
> In the Redux Async Data Flow, we first handle a user event, like a button click, by calling `dispatch()` with an action. The action is intercepted by middleware, which can perform async logic, such as making API calls. Once the async logic is completed, the middleware dispatches a real action object, which is then handled by the reducer to update the state.

**How are we accommodating async in our Redux app?**
> We accommodate async in our Redux app by using thunk functions, which are functions that get dispatched instead of plain action objects. Thunk functions have access to `dispatch` and `getState`, allowing us to write async logic and dispatch actions based on the async results. We use the Redux Thunk middleware to handle these thunk functions in our app.

## thunk middleware

**Why would you need `redux-thunk` middleware?**
> Redux Thunk middleware is used when we want to write action creators that have some logic inside them and can interact with the Redux store.

**Redux Thunk middleware allows you to write action creators that return a ____ instead of an action.**
> function

**Describe how any return value from the inner thunk function will be made available.** 
> Any return value from the inner thunk function will be available as the return value of the dispatch function itself.

## Reflection

**What are your learning goals after reading and reviewing the class README?**
> Learning goals are to understand what Redux middleware is, why Thunk middleware is necessary for handling asynchronous actions in Redux, and how to perform asynchronous actions and use lifecycle hooks in Redux.
