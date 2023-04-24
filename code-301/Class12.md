# Class 12 CRUD

#### Link to article: [Status Codes Based On REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)
#### Link to article: [Build A REST API With Node.js, Express, & MongoDB](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw)

> 

***

## Status Codes Based On REST Methods

**In your own words, describe what each group of status code represents:**
>
> - 100’s = Informational responses indicate the server is processing the request.
> - 200’s = Success responses indicate the server processed the request and returned the expected content.
> - 300’s = Redirection responses that indicate the client must take additional action to complete the request, such as following a new URL or using a cached response.
> - 400’s = Client errors indicate the server couldn't process the request due to a client-side error.
> - 500’s = Server errors indicate an internal error, such as a misconfiguration or unhandled exception, prevented the server from processing the request.


**What is a status code 202?**
> Status code 202 means the request has been accepted but processing is not yet complete, and the result may not be immediately available.


**What is a status code 308?**
> Status code 308 means the requested resource has been permanently moved to a new URL and the client should update its bookmarks.


**What code would you use if an update didn’t return data to a client?**
> You would use status code 204 - "No Content" to indicate that the update was successful but there is no data to return to the client.


**What code would you use if a resource used to exist but no longer does?**
> You would use status code 410 - "Gone" to indicate that the requested resource is no longer available and has been permanently removed.


**What is the ‘Forbidden’ status code?**
> The 'Forbidden' status code (403) means that the client does not have permission to access the requested resource.

***

## Build A REST API With Node.js, Express, & MongoDB

**Why do we need to pull our MongoDB database string out of our server and put it into our .env?**
> We need to put the MongoDB database string into the .env file to keep it confidential and prevent unauthorized access or modification to the database.


**What is middleware?**
> Middleware is software that acts as a bridge between different applications or systems.


**What does app.use(express.json()) do?**
> app.use(express.json()) is a middleware function in Express.js that parses incoming JSON data in the request body and makes it available in the request object as req.body.


**What does the /:id mean in a route?**
> The /:id specifies a dynamic parameter in the route URL that can be used to retrieve a resource based on its unique identifier.


**What is the difference between PUT and PATCH?**
> The main difference between PUT and PATCH HTTP methods is that PUT replaces the entire resource, while PATCH updates only the specified fields of the resource.


**How do you make a default value in a schema?**
> To make a default value in a schema, set the default property of the field to the desired default value when defining the schema in Mongoose.


**What does a 500 error status code mean?**
> A 500 error status code indicates an internal server error, which means that the server encountered an unexpected condition that prevented it from fulfilling the request.

**What is the difference between a status 200 and a status 201?**
> A status 200 indicates a successful response to a GET or POST request, while a status 201 indicates a successful creation of a new resource in response to a POST request.