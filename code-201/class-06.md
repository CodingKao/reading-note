# Class 5 Notes

# Problem Domain, Objects, and the DOM

#### Link to article: [JavaScript object basics](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics)
#### Link to article: [Introduction to the DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)
#### Link to article: [How to Solve Programming Problems](https://simpleprogrammer.com/solving-problems-breaking-it-down/)
#### Link to article: [What’s the Difference Between Primitive Values and Object References in JavaScript?](https://betterprogramming.pub/intermediate-javascript-whats-the-difference-between-primitive-values-and-object-references-e863d70677b)

> Javascript Object Basics describe the syntax used to create and interact with objects in Javascript. The Document Object Model (DOM) is an interface that allows programs and scripts to dynamically access and update the content, structure, and style of a document. The DOM is used to represent and manipulate HTML and XML documents


***

## JavaScript Object Basics

**How would you describe an object to a non-technical friend you grew up with?**
> A JavaScript object is like a box of information. It can store data and pieces of code that can be used to do things. It's like a "dictionary" of information that can be used to look up values or do actions. It helps keep your code organized and efficient.

**What are some advantages to creating object literals?**
> Object literals provide an easy way to create and manage objects in a simple, organized way. They are flexible and allow you to quickly and easily add, remove, and update properties. They also provide a clean and concise syntax that makes it easy to read and understand code. Additionally, object literals are easy to pass around functions and they don’t require the use of the new keyword.

**How do objects differ from arrays?**
> Objects are key-value pairs while arrays are ordered lists of items. Objects use strings as keys and can contain any type of data. Arrays are indexed with numbers and can only contain the same type of data. Objects are better for storing data that is associated with a specific identifier, while arrays are better for ordered lists of data.

**Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.**
> Dot notation is generally preferred over bracket notation because it is more succinct and easier to read. However there are some cases where you have to use brackets. For example, if an object property name is held in a variable, then you can't use dot notation to access the value, but you can access the value using bracket notation.

**Evaluate the code below. What does the term this refer to and what is the advantage to using this?**
> In the context of the humanAge method, the keyword this refers to the object dog itself. Using this allows the method to access and use the properties of the dog object without needing to explicitly reference the object by name.


***

## Introduction to the DOM

**What is the DOM?**
> The Document Object Model (DOM) is a programming interface for web documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects; that way, programming languages can interact with the page.

**Briefly describe the relationship between the DOM and JavaScript.**
> The DOM (Document Object Model) is a programming interface that allows JavaScript to interact with HTML and XML documents. Through the DOM, JavaScript can access and modify the content, structure, and style of a document. The DOM is the bridge between JavaScript and webpages, allowing JavaScript to manipulate webpages in response to user interactions and other events.
