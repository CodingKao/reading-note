# Class 27: `useState()` Hook

#### Link to article: [Thinking in React](https://react.dev/learn/thinking-in-react)

#### Link to article: [State: A Component’s Memory](https://react.dev/learn/state-a-components-memory)


***

**Bookmarks**

#### Link to article: [Passing Props to a Component](https://react.dev/learn/passing-props-to-a-component)

#### Link to article: [Rendering Lists](https://react.dev/learn/rendering-lists)

#### Link to article: [State as Snapshot](https://react.dev/learn/state-as-a-snapshot)

#### Link to article: [useState hook](https://react.dev/reference/react/useState)


***

## Thinking in React

**Summarize the five steps of thinking in react.**
>
> Step 1: Break the UI into a component hierarchy
> - Identify the components in the mockup and arrange them into a hierarchy.
> - Components include FilterableProductTable, SearchBar, ProductTable, ProductCategoryRow, and ProductRow.
>
> Step 2: Build a static version in React
>- Implement the app without interactivity, focusing on rendering the UI from the data model.
> - Build reusable components that receive data through props.
>
> Step 3: Find the minimal but complete representation of UI state
>
> - Identify the minimal set of changing data (state) that the app needs to remember.
> - Determine which pieces of data are state by considering if they remain unchanged, are passed via props, or can be computed based on existing state or props.
> 
> Step 4: Identify where your state should live
>
> - Determine which component should own and manage the state.
> - Identify the components that render based on the state and find their closest common parent component.
> - Decide where the state should live based on the hierarchy, either in the common parent or a component above it.
>
> Step 5: Add inverse data flow
> - Support data flowing from the form components back to the state in FilterableProductTable.
> - Update the state in response to user input.
Implement data flow explicitly to ensure the state is updated correctly.

## State: A Component’s Memory

**What is one reason a local variable isn’t sufficient for managing a React component?**
> A local variable isn't sufficient for managing a React component because it doesn't persist between renders and doesn't trigger re-rendering when it changes.

**What is the argument to the useState hook, and what are the two parts of its return array?**
> The argument to the useState hook is the initial value of the state variable. The return array consists of the state variable and the setter function.


**How can Component A access state from Component B?**
> Component A can access state from Component B by passing the state data as props from Component B to Component A.


## Reflection

**What are your learning goals after reading and reviewing the class README?**
> Understand the pros and cons of functional and class components, learn how to use the state hook for managing state in functional components, and use the effect hook to manage state at different times during a component's lifecycle.