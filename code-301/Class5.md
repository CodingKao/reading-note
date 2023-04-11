# Class 5 Putting it all together

#### Link to article: [React Docs - Thinking in React](https://react.dev/learn/thinking-in-react)
#### Link to article: [Higher-Order Functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)

> 

***

## React Docs - Thinking in React

**What is the `single responsibility principle` and how does it apply to components?**
> The `single responsibility principle` is the principle that a component should only have one job, making it easier to understand, test, and maintain.

**What does it mean to build a `static` version of your application?**
> Building a `static` version of your application means creating a version that renders the UI based on a fixed set of data, without any interactivity or dynamic behavior.


**Once you have a static application, what do you need to add?**
> Once you have a static application, you need to add interactivity and dynamic behavior by incorporating state and event handling to make it fully functional.

**What are the three questions you can ask to determine if something is state?**
> - Is it passed in from a parent via props?
> - Does it remain unchanged over time?
> - Can it be computed based on any other state or props in the component?

**How can you identify where state needs to live?**
> You can identify where state needs to live by finding a common owner component that needs the state data or determining the component that renders the component requiring the state data.

***

## Higher-Order Functions

**What is a `higher-order function`?**
> A `higher-order function` is a function that takes one or more functions as arguments or returns a function as its result.

**Explore the `greaterThan` function as defined in the reading. In your own words, what is line 2 of this function doing?**
> Line 2 of the greaterThan function is creating and returning a new function that takes a number m as an argument and returns a Boolean value indicating whether m is greater than the number n that was passed into the greaterThan function

**Explain how either `map` or `reduce` operates, with regards to higher-order functions.**
> `Map` is a higher-order function that operates by taking an input array and applying a function to each element to produce a new array, while `reduce` takes an input array and reduces it to a single value by applying a function to each element and accumulating the result.