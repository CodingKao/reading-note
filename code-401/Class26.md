# Class 26: Component Based UI

#### Link to article: [React Quick Start](https://react.dev/learn)

#### Link to video: [Render and Commit](https://react.dev/learn/render-and-commit)


***

**Bookmarks**

#### Link to article: [Your First Component](https://react.dev/learn/your-first-component)

#### Link to article: [Importing and Exporting Components](https://react.dev/learn/importing-and-exporting-components)

#### Link to article: [Writing Markup with JSX](https://react.dev/learn/writing-markup-with-jsx)

#### Link to article: [sass cheatsheet](https://devhints.io/sass)

#### Link to article: [react cheatsheet](https://devhints.io/react)

***

## React Quick Start

**What are the building blocks of a React app?**
> The building blocks of a React app are components, which are reusable pieces of code that handle specific parts of the user interface.

**What is the difference between an HTML element and a React component?**
> An HTML element is a basic part of a web page, while a React component is a reusable and more advanced part with additional functionality.

**What is JSX and why do we use it?**
> JSX is a syntax extension for JavaScript used in React to write HTML-like code within JavaScript. It helps combine HTML and JavaScript, making it easier to build dynamic user interfaces.

**Describe the process of embedding JavaScript expressions in JSX.**
> To embed JavaScript expressions in JSX, we use curly braces {}. We can place the expression inside the braces, and it will be evaluated and rendered within the JSX.

**Does React or JSX have any special features for iteration or conditional logic?**
> Yes, React and JSX provide special features like mapping arrays to create lists and using conditional statements like if/else or ternary operators for conditional rendering.

**How does React know to respond to a user’s inputs?**
> React knows to respond to a user's inputs by using event handling, which listens for user actions like clicks or typing, triggering corresponding functions or updates.

**What word indicates that a React component manages data with a Hook?**
> The word "useState" indicates that a React component manages data with a Hook.

**How can two react components share data?**
> Two React components can share data by passing information through props, which are properties passed from a parent component to its child component.


## Render and Commit

**What are the three steps of refreshing a React UI?**
> 
>- Update the component's state.
>- Re-render the component.
>- Reflect the changes in the user interface.

**How do you trigger updates to a component after the initial render?**
> To trigger updates to a component after the initial render, we can modify the component's state or props, which will trigger a re-rendering of the component.


**Does React recreate DOM nodes on every rerender?**
> No, React efficiently updates only the necessary parts of the DOM instead of recreating all the DOM nodes on every rerender.


**After React has updated the DOM, what still needs to happen before the user sees the change?**
> After React has updated the DOM, the browser needs to paint/render the updated DOM before the user can see the change.


## Additional Questions

**Note the naming conventions in the Airbnb React/JSX Style Guide. What pattern(s) do you see?**
> 
>- Use PascalCase for filenames and React components.
>- Use camelCase for instances of React components.
>- Use index.jsx as the filename for root components in a directory.
>- Use a composite of the higher-order component's name and the passed-in component's name for displayName.
>- Avoid using DOM component prop names for different purposes.

**Looking ahead at this module’s course schedule, What do you look forward to learning?**
> I look forward to learning about React function components, state and effect hooks, reducer hooks, and hash tables implementation.


**What are your learning goals after reading and reviewing the class README?**
> My learning goals after reading the class README are to understand component-based UI systems, master React's basics, create and style components, handle events, and manage component state.