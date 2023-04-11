# Class 3 Passing Functions as Props

#### Link to article: [React Docs - lists and keys](https://legacy.reactjs.org/docs/lists-and-keys.html)
#### Link to article: [The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

> 

***

## React Docs - lists and keys

**What does .map() return?**
> `.map()` returns a new array with the same length as the original array, where each element has been transformed based on the return value of the callback function provided to `.map()`.

**If I want to loop through an array and display each value in JSX, how do I do that in React?**
> In React, you can use the `.map()` method to loop through an array and return a new array of JSX elements, each representing a value in the original array. You can then render the resulting array of JSX elements within a parent component using curly braces { }.


**Each list item needs a unique ____.**
> Each list item in React needs a unique key prop. The key prop helps React to keep track of the items in the list and efficiently update the DOM when changes occur.

**What is the purpose of a key?**
> The purpose of a key in React is to help identify which items in a list have changed, been added, or been removed, and to help React efficiently update the DOM.

***

## The Spread Operator

**What is the spread operator?**
> In React, the spread operator `...` is used to pass props or state as individual key-value pairs into a new object or component.

**List 4 things that the spread operator can do.**
> - Concatenate arrays
> - Merge objects
> - Copy an array or object
> - Pass props or state as individual key-value pairs into a new object or component

**Give an example of using the spread operator to combine two arrays.**
> const arr1 = [1, 2, 3];
>
> const arr2 = [4, 5, 6];
>
> const combinedArr = [...arr1, ...arr2];
>
> console.log(combinedArr);
>
> Output: [1, 2, 3, 4, 5, 6]

**Give an example of using the spread operator to add a new item to an array.**
> const arr = [1, 2, 3];
>
> const newItem = 4;
>
> const newArr = [...arr, newItem];
>
> console.log(newArr);
>
> Output: [1, 2, 3, 4]

**Give an example of using the spread operator to combine two objects into one.**
> const obj1 = { a: 1, b: 2 };
>
> const obj2 = { c: 3, d: 4 };
>
> const combinedObj = { ...obj1, ...obj2 };
>
>console.log(combinedObj); 
>
> Output: { a: 1, b: 2, c: 3, d: 4 }


## How to Pass Functions Between Components

**In the video, what is the first step that the developer does to pass functions between components?**
> created function called 'increment' and pass in a 'name', created variable called 'ppl' assigned it 'this.state.people.map()', passed in 'P' object for person, then did 'if(p.name === name) {p.count++;} and then return p

**In your own words, what does the increment function do?**
> An increment function is used to increase the value of a variable or state property by a specified amount.

**How can you pass a method from a parent component into a child component?**
> You can pass a method from a parent component into a child component by including the method as a prop in the child component.

**How does the child component invoke a method that was passed to it from a parent component?**
> The child component can invoke a method that was passed to it from a parent component by calling the method through the props.
