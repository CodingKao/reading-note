# Class 3 Express REST API

#### Link to article: [Review: ES6 Classes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)
#### Link to article: [Using Express Routing](https://expressjs.com/en/guide/routing.html)
#### Link to article: [Express Routing?](https://www.digitalocean.com/community/tutorials/learn-to-use-the-new-router-in-expressjs-4)


***

## Review: ES6 Classes

**Classes are a template for creating ____.**
> JS classes: object creation templates that hold data and code, built on prototypes, with unique syntax and semantics.

**Can a class declaration be hoisted?**
> No, class declarations in JavaScript are not hoisted. They need to be declared before they can be accessed or used in the code.


**How would you describe a constructor and contextual “this” to a non-technical friend?**
> A constructor is like a blueprint for creating objects, and "this" refers to the object being created.

## Using Express Routing

**Within Express, what does routing refer to?**
> Routing in Express refers to the process of directing incoming requests to their respective handlers or endpoints.

**What is the difference between a route path and a route method?**
> A route path in Express defines the URL pattern, while a route method specifies the HTTP verb used to access that path.

**When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?**
> `next` is used to pass control to the next middleware/route handler. If received, you must invoke `next()` to proceed to the `next` function in the middleware chain.

## Express Routing

**What is an Express Router?**
> Express Router is a modular routing middleware that allows grouping and organizing routes in separate files for better code organization.

**By what mean do we initialize express.Router() in an express server?**
> By calling the `express.Router()` function and assigning it to a variable, typically named `router`, in the Express server.

**What do we use route middleware for?**
> We use route middleware in Express to perform additional operations on the request and response objects before passing control to the route handler.

## Reflection
**What are your learning goals after reading and reviewing the class README?**
> My learning goals are to gain a better understanding of ES6 features, learn how to use express routing effectively, and become proficient in working with express middleware and routing.