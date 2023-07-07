# Class 37: Reading: Redux - Combined Reducers

#### Link to article: [Multiple Reducers Example](https://canvas.instructure.com/courses/6745216/discussion_topics/18080594/submit)

#### Link to article: [Redux Docs: Using Combined Reducers](https://canvas.instructure.com/courses/6745216/discussion_topics/18080594/submit)

#### Link to article: [Redux Docs: Combined Reducer Syntax](https://canvas.instructure.com/courses/6745216/discussion_topics/18080594/submit)

***

**Bookmarks**


***

## Multiple Reducers Example

**Why create multiple reducers?**
> We create multiple reducers to handle different pieces of data in our application. Each reducer is responsible for managing the state of a specific data domain or feature. This helps to keep our code organized and maintainable.

**How would you combine multiple reducers?**
> To combine multiple reducers, we use the `combineReducers` function from Redux. We import it from the Redux library and pass an object to it, where each key represents a piece of state and its corresponding reducer function.

**How will you manage state as an immutable object? why?**
> We manage state as an immutable object to ensure data integrity and prevent unintended side effects. Instead of directly modifying the state, we create a new state object with the necessary changes. This allows us to track the changes and maintain a reliable history of state transitions, making debugging and testing easier. Immutable state helps to avoid unexpected bugs caused by shared references and ensures predictable behavior in our application.

## Redux Docs: Using Combined Reducers

**combineReducers is a utility function to simplify the most common use case when writing ___ _____ .**
> Redux reducers.

**Explain how combineReducers assembles the new state tree.**
> combineReducers assembles the new state tree by calling each slice reducer with its current slice of state and the current action. It combines the updated slices into the new state object.

**How would you define initial state in an app using combineReducers** 
> To define initial state in an app using combineReducers, you can either provide preloadedState as the second argument to createStore or have the root reducer return the initial state value when the state argument is undefined.

## Redux Docs: Combined Reducer Syntax

**Why will you want to split your reducing functions as your app becomes more complex?**
> As your app becomes more complex, splitting your reducing functions allows you to manage independent parts of the state and keep the logic organized.

**The _____ helper function turns an object whose values are different reducing functions into a single reducing function you can pass to ____.**
> The `combineReducers` helper function turns an object whose values are different reducing functions into a single reducing function you can pass to `createStore`.

**What is a popular convention when naming reducers?**
> A popular convention when naming reducers is to name them after the state slices they manage. This convention allows you to use ES6 property shorthand notation when combining reducers.


## Reflection

**What are your learning goals after reading and reviewing the class README?**
> To understand how to implement multiple reducers in a Redux app to manage complex shared state between components.
