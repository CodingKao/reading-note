# Class 29: Advanced State with Reducers

#### Link to article: [Extracting State Logic into a Reducer](https://react.dev/learn/extracting-state-logic-into-a-reducer)

***

**Bookmarks**

#### Link to article: [useReducer hook](https://react.dev/reference/react/useReducer)

#### Link to article: [Keeping Components Pure](https://react.dev/learn/keeping-components-pure)

#### Link to article: [Queueing a Series of State Updates](https://react.dev/learn/queueing-a-series-of-state-updates)


***

## Extracting State Logic into a Reducer

**What is the motivation for adding a reducer?**
> The motivation for adding a reducer is to consolidate and manage the complex state logic of a component in a separate function, enhancing code readability and debugging capabilities.


**What are actions in the context of a reducer? How are they different than setting state directly?**
> Actions in the context of a reducer are objects that describe the user's intent or interaction, dispatched from event handlers. They differ from setting state directly by specifying "what the user just did" instead of directly updating state.


**What common list operation is useReduce named for, and why?**
> The `useReducer` hook is named after the common list operation called "reduce" because it helps in reducing complex state updates to a simpler form by utilizing a reducer function.


**When should you switch from useState to useReducer?**
> You should switch from `useState` to `useReducer` when you encounter frequent bugs related to incorrect state updates and want to add more structure to your code.

## Reflection

**What are your learning goals after reading and reviewing the class README?**
> To understand and implement state management using reducers and the useReducer() hook in functional components.