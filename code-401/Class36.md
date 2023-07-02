# Class 36: Reading: Application State with Redux

#### Link to article: [Dan Abramov Redux Tutorials](https://canvas.instructure.com/courses/6745216/discussion_topics/18080594/submit)

***

**Bookmarks**
#### Link to article: [worlds easiest guide to redux](https://www.freecodecamp.org/news/understanding-redux-the-worlds-easiest-guide-to-beginning-redux-c695f45546f6)

#### Link to article: [testing reducers](https://medium.com/@netxm/testing-redux-reducers-with-jest-6653abbfe3e1)

#### Link to article: [Redux Docs](https://redux.js.org/)
***

## Dan Abramov Redux Tutorials

**What is the first principle of Redux?**
> The first principle of Redux is that no matter how simple or complex your app is, you represent the whole app's state as a single JavaScript object, and every change that happens in the app is carefully tracked and stored in that object.


**What is a store and what do we use our reducers for within that store?:**
> A store is a place where we keep track of the current state of our application. We use reducers in the store to update the state based on the actions we dispatch, like adding or removing items, and they make sure that the state changes in a controlled and predictable way.


**Name three Redux store methods given to us by createStore and describe their use.**
> - `getState()`: It returns the current state of the application. You can use it to access the current data stored in the Redux store.
> - `dispatch(action)`: It is used to send an action to the store, which triggers the state update. Actions describe what needs to change in the application's state.
>- `subscribe(callback)`: It allows you to register a callback function that will be called whenever there is a state change in the store. This is useful for updating the user interface to reflect the new state.


**Explain to a non-technical recruiter what `combineReducers()` does and why it is useful.**
> `combineReducers()` is a function in Redux that helps put together different reducer functions into one, making it easier to manage and update different parts of an application's state. It's useful because it helps organize the code and allows developers to handle different parts of the state separately, which can make the application more scalable and maintainable.



## Reflection

**Looking ahead at this module’s course schedule, What do you look forward to learning?**
> I'm excited to learn about how to use Redux with React to manage the state of my applications, including how to create reducers, actions, and combine them. I'm also curious about asynchronous actions and advanced ways to use Redux to make my projects even better!

**What are your learning goals after reading and reviewing the class README?**
> To understand how to use Redux to manage the state of my React applications. I want to learn about creating a Redux store, using reducers and actions to modify the state, and connecting my components to the store to access the state and trigger actions.
