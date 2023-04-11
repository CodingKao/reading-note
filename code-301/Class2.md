# Class 2 State and Props

#### Link to article: [React lifecycle](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)
#### Link to article: [React State Vs Props](https://www.youtube.com/watch?v=IYvD9oBCuJI)

> 

***

## React lifecycle

**Based off the diagram, what happens first, the ‘render’ or the `componentDidMount`?**
> The diagram shows that the `render` comes before the `componentDidMount`.

**What is the very first thing to happen in the lifecycle of React?**
> The very first thing to happen in the lifecycle of a React component is the "mounting" phase. This is when the component is initialized and inserted into the DOM.


**Put the following things in the order that they happen: `componentDidMount`, `render`, `constructor`, `componentWillUnmoun`t, `React Updates`**
> 1. Constructor: This is called when a component is initialized and sets up the initial state and props.
> 
> 2. Render: This is called during the "mounting" and "updating" phases, and returns a description of the component's UI in the form of a React element.
>
> 3. ComponentDidMount: This is called immediately after a component is mounted into the DOM, and is often used to fetch data or set up event listeners.
>
> 4. React Updates: During the "updating" phase, React may update the props or state of a component based on changes in the application. This triggers a re-render of the component, starting again with the render method.
>
> 5. ComponentWillUnmount: This is called immediately before a component is unmounted from the DOM, and is often used to clean up any resources used by the component, such as event listeners.

**What does `componentDidMount` do?**
> `componentDidMount` is a React component lifecycle method that is called immediately after a component is mounted into the DOM, and is often used to fetch data or set up event listeners.

***

## React State Vs Props

**What types of things can you pass in the props?**
> In React, you can pass various types of data in the props of a component, including strings, numbers, booleans, objects, arrays, functions, and other React elements. Props are read-only and cannot be modified by the child component directly.

**What is the big difference between props and state?**
> In React, props are passed down from a parent component to a child component and are read-only, while state is managed within a component and can be updated by the component itself.

**When do we re-render our application?**
> In React, a component is re-rendered when its state or props change. The re-rendering can also be triggered by changes in the parent component that cascade down to the child component via props.

**What are some examples of things that we could store in state?**
> In React, we can store various types of data in state, including form inputs, user events, UI state (such as whether a modal is open or closed), and data fetched from an API or received from a parent component via props.