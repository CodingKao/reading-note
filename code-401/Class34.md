# Class 34: Reading: API Integration

#### Link to article: [Review API Server Build](https://codefellows.github.io/code-401-javascript-guide/curriculum/apps-and-libraries/api-server/)
#### Link to article: [Review Auth Server Build](https://codefellows.github.io/code-401-javascript-guide/curriculum/apps-and-libraries/auth-server/)

***

**Bookmarks**

***

## Review API Server Build

**Explain the different between a query string parameter and a path parameter.**
> The difference between a query string parameter and a path parameter is that a query string parameter is appended to the URL after a question mark and is used to provide additional information to the server, while a path parameter is a part of the URL path itself and is used to identify a specific resource or endpoint.

**What would our API URL with a path id parameter be given the following information:**
> - Domain: `http://our-site.com`
> - `v3`
> - model name: `stuff`
> - id: `things`
>
> The API URL with a path id parameter would be: http://our-site.com/api/v3/stuff/things.

**We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend.**
> We have created an interface for our API that allows us to communicate with our server. This interface follows a specific structure in the URL, such as "http://amazingapi.com/api/v1/products/12345". It helps us retrieve, create, update, or delete data by specifying the desired action and the type of data we want to work with.


## Review Auth Server Build

**Describe how you would use middleware to implement basic and bearer auth.**
> To implement basic and bearer authentication using middleware, you would create separate middleware functions that validate the user's credentials and bearer token, respectively, and then use these middleware functions in the appropriate routes to authenticate and authorize the user before allowing access to protected resources.

**Describe the handshake necessary to implement OAuth.**
> To implement OAuth, the handshake process involves a user granting permission to a third-party service (like Google or GitHub) to access their information, and then the service providing an authorization token to the application, which can be used to authenticate the user and access their data on their behalf.

**Describe how Role Based Access Control works to a non-technical friend.**
> Role Based Access Control (RBAC) is like having different levels of keys to open different doors: each person is assigned a specific role that determines what they can do, and they can only access areas or perform actions that are allowed for their specific role, making sure that everyone has the right level of access and security in a system.
