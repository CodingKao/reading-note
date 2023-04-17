# Class 8 APIs

#### Link to article: [API Design Best Practices](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design)
> 

***

## API Design Best Practices

**What does REST stand for?**
> REST stands for "Representational State Transfer", which is an architectural style used for designing web APIs that are scalable, flexible, and easy to maintain.

**REST APIs are designed around a ____.**
> REST APIs are designed around a set of standard HTTP methods (such as GET, POST, PUT, and DELETE) and the representation of resources through URIs (Uniform Resource Identifiers).

**What is an identifier of a resource? Give an example.**
> An identifier of a resource is a unique string of characters used to identify a specific resource in a web API, such as a URL or URI, with an example being "https://example.com/api/posts/123" as the identifier for a specific blog post in a REST API.

**What are the most common HTTP verbs?**
> The most common HTTP verbs are GET, POST, PUT, PATCH, DELETE, OPTIONS, and HEAD.

**What should the URIs be based on?**
> URIs should be based on the resources that they represent, rather than the actions that can be performed on them, to follow the principles of RESTful API design.

**Give an example of a good URI.**
> A good example of a URI for a RESTful API would be "https://example.com/api/posts/123" which uniquely identifies a specific blog post resource.

**What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?**
> A 'chatty' web API is one that requires a large number of small and frequent requests to perform a single operation, which is generally considered a bad thing as it can result in increased network traffic, latency, and resource usage.

**What status code does a successful GET request return?**
> A successful GET request returns a status code of 200 OK, along with the requested resource in the response body.

**What status code does an unsuccessful GET request return?**
> A failed GET request returns a specific error status code, such as 404 Not Found or 401 Unauthorized.

**What status code does a successful POST request return?**
> POST success: 201 Created with new resource representation.

**What status code does a successful DELETE request return?**
> Successful DELETE request returns 204 No Content.