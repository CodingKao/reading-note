# Class 39: Reading: Redux - Additional Topics

#### Link to article: [Redux Toolkit (RTK)](https://redux-toolkit.js.org/introduction/getting-started)

#### Link to article: [MobX](https://mobx.js.org/getting-started.html)

#### Link to article: [Tutorial](https://redux-toolkit.js.org/tutorials/overview)

***

**Bookmarks**

#### Link to article: [Redux Toolkit (RTK)](https://redux-toolkit.js.org/)

#### Link to article: [HookState](https://hookstate.js.org/)

***

## Redux Toolkit (RTK)

**What concerns are addressed by Redux Toolkit?**
> Redux Toolkit addresses concerns about the complexity of configuring a Redux store, the need for multiple packages to make Redux useful, and the boilerplate code required by Redux.

**What does `configureStore()` do?**
> configureStore() is a function provided by Redux Toolkit that wraps createStore() and simplifies the configuration process for creating a Redux store. It automatically combines slice reducers, includes middleware such as redux-thunk, and enables the use of the Redux DevTools Extension.

**How would I use `createSlice()`?**
> createSlice() is a function provided by Redux Toolkit that allows you to define a slice reducer with corresponding action creators and action types. You would use it by passing an object of reducer functions, a slice name, and an initial state value to generate the slice reducer and associated actions.

## MobX

**What is Mobx?**
> MobX is a state management solution that helps manage and update the state of an application in a simple and scalable way. It is often used in combination with React.

**How does MobX make it “impossible” to produce an inconsistent state?**
> MobX ensures that the state of an application remains consistent by automatically updating any values that are derived from the state. This means that whenever the state changes, all dependent values are updated automatically.

**How would we build a reactive user interface?** 
> To build a reactive user interface with MobX, we can use the observer wrapper from the mobx-react-lite package. This wrapper keeps the components in sync with the state, so they automatically re-render whenever relevant data changes, eliminating the need for manual state management in React components.

## Tutorial

**What take-away(s) did this tutorial provide?**
> This tutorial provides an overview of different tutorials and resources for learning Redux and Redux Toolkit. It suggests specific tutorials for different needs, such as quick start guides, building real-world applications, understanding the fundamentals of Redux, migrating from vanilla Redux to Redux Toolkit, and using Redux Toolkit with TypeScript. It also mentions a livestream example that demonstrates using Redux Toolkit with React and TypeScript.


## Reflection

**What are your learning goals after reading and reviewing the class README?**
>  learning goals are to understand alternate means of managing a Redux store, such as using Ducks and Redux Toolkit, and to learn about other ways to manage state, like MobX. I also want to explore how Redux Toolkit simplifies the process of building reducers and actions by providing a standardized framework.
