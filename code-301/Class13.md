# Class 13 More CRUD

#### Link to article: [CRUD Basics](https://medium.com/geekculture/crud-operations-explained-2a44096e9c88)
#### Link to article: [Speed Coding: Building a CRUD API](https://www.youtube.com/watch?v=EzNcBhSv1Wo)

> 

***

## CRUD Basics

**Which HTTP method would you use to update a record through an API?**
> To update a record through an API, you would typically use the HTTP method "PUT" or "PATCH" depending on whether you need to update the entire resource or just a portion of it.


**Which REST methods require an ID parameter?**
> The REST methods that require an ID parameter are typically "GET", "PUT", "PATCH", and "DELETE".


***

## Speed Coding: Building a CRUD API

**What’s the relationship between REST and CRUD?**
> REST is a way to make web services communicate with each other using a set of rules. CRUD is a way to do basic things with data, like creating, reading, updating, and deleting.

The relationship between REST and CRUD is that when we use REST to build web services, we often use CRUD to work with the data that the web services are handling. REST gives us the structure to make web services, and CRUD gives us the basic tools to work with the data.

**If you had to describe the process of creating a RESTful API in 5 steps, what would they be?**
> 1. Identify the resources: Decide what data or functionality you want to expose through the API.
>
>2. Define the API endpoints: Choose the URLs that clients will use to access the API and specify which HTTP methods (like GET, POST, PUT, and DELETE) will be used to interact with each endpoint.
>
>3. Implement the endpoints: Write code to handle each API endpoint and return the appropriate data or perform the desired functionality.
>
>4. Test the API: Verify that the API works as expected and responds correctly to various types of requests.
>
>5. Document the API: Provide clear and concise documentation for developers who will be using the API, including details on the available endpoints, request and response formats, and any required authentication or authorization.