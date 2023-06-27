# Class 31: Context API

#### Link to article: [Choosing the State Structure](https://react.dev/learn/choosing-the-state-structure)
#### Link to article: [Passing State Deeply with Context](https://react.dev/learn/passing-data-deeply-with-context)

***

**Bookmarks**

#### Link to article: [Sharing State Between Components Preserving and Restting State](https://react.dev/learn/preserving-and-resetting-state)



***

## Choosing the State Structure

**Summarize the five principles for structuring state.**

> 1. Group related state: If you always change two or more state things together, you can put them in one group to keep them organized.
> 2. Avoid contradictions in state: Don't make the state in a way that different state things can fight or disagree with each other. It can cause mistakes, so try to avoid it.
>
> 3. Avoid redundant state: If you can figure out some information using the props or existing state, don't store the same information again. It can make things confusing and lead to errors.
>
> 4. Avoid duplication in state: When you have the same data in different state things or inside other groups, it's hard to keep them all the same. So, if you can, try to reduce the number of duplicates.
>
> 5. Avoid deeply nested state: Having state things in many layers can be tricky to change and understand. It's better to keep the state in a simple and flat way when you can.


## Passing State Deeply with Context

**What problem do Contexts aim to solve?**
> Contexts aim to solve the problem of passing data through multiple components in a tree, especially when the data needs to be accessed by components deep in the tree.

**What is one technique to try before useContext?**
> One technique to try before useContext is to pass props down through the component tree.


**What hook complements useContext for complex applications?**
> The hook that complements useContext for complex applications is the useReducer hook.
