# Class 4 React and Forms

#### Link to article: [React lifecycle](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)
#### Link to article: [React State Vs Props](https://www.youtube.com/watch?v=IYvD9oBCuJI)

> 

***

## React Docs - Forms

**What is a ‘Controlled Component’?**
> A controlled component in React is a form element whose value is managed by the component's state, and the component controls its behavior based on user input through state updates.

**Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.**
> It's better to update the state with the user's responses as soon as they enter them rather than waiting for them to submit the form, as it allows for real-time feedback and improves usability.


**How do we target what the user is entering if we have an event handler on an input field?**
> We can target what the user is entering by accessing the value property of the event object in the event handler function. This property holds the current value of the input field.

***

## The Conditional (Ternary) Operator Explained

**Why would we use a ternary operator?**
> We use a ternary operator as a shorthand way of writing conditional statements. It allows us to write more concise code and can make the code easier to read in some cases.

**Rewrite the following statement using a ternary statement:**
```if(x===y){
console.log(true);
} else {
console.log(false);
}
```
>
```x === y ? console.log(true) : console.log(false);```
