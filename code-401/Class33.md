# Class 33: Reading: `<Login />` and `<Auth />`

#### Link to article: [What is Role Based Access Control (RBAC)?](https://www.digitalguardian.com/blog/what-role-based-access-control-rbac-examples-benefits-and-more)
#### Link to article: [react-cookie library](https://www.npmjs.com/package/react-cookie)
#### Link to article: [react-cookies component](https://www.npmjs.com/package/react-cookies)

***

**Bookmarks**

***

## What is Role Based Access Control (RBAC)?

**What is Role Based Access Control (RBAC)?**
> Role-Based Access Control (RBAC) is a method of restricting network access based on a person's role within an organization, ensuring that employees only have access to the information necessary for their job.

**Share some an example of RBAC including all possible CRUD operations and correlating roles.**
> In an RBAC system, different roles can have specific permissions for Create, Read, Update, and Delete (CRUD) operations. For example, in a file management system:
>
> - The "Admin" role may have permissions to create, read, update, and delete files.
> - The "Manager" role may have permissions to read and update files but not create or delete them.
> - The "Employee" role may have permissions only to read files but not create, update, or delete them.

**What are the Benefits of RBAC?**
> The benefits of RBAC include reducing administrative work and IT support, maximizing operational efficiency, and improving compliance with regulations. RBAC helps streamline access control, minimizes errors in assigning permissions, enables quick role changes, enhances productivity, and ensures better data privacy and confidentiality.


## react-cookie library

**Describe some `react-cookie` features.**
> React Cookie is a library for managing cookies in React applications. Its features include:
>
> - CookiesProvider component for accessing and modifying cookies throughout the component tree.
> - Hook-based API (useCookies) for reading, writing, and removing cookies in functional components.
> - withCookies Higher-Order Component (HOC) for providing cookie access to any component.
> - Support for server-side rendering (SSR) by passing cookies from the server to the CookiesProvider.
> - Functions for getting, setting, and removing individual cookies.
> - Cookie options for customization, such as path, expires, maxAge, domain, secure, httpOnly, and sameSite.
>
>In summary, React Cookie simplifies cookie management in React with a concise API and support for various scenarios.

**Describe some `react-cookies` features.**
> React Cookies is a lightweight library for handling cookies in React applications. Some of its features include:
>
> - Simple API: React Cookies provides a simple and intuitive API for working with cookies in React components.
>
> - Cross-browser support: It offers consistent cookie handling across different browsers, ensuring compatibility and reliable behavior.
>
> - Read and write cookies: You can easily read and write cookies using the provided functions. > The library abstracts the complexities of cookie management, making it straightforward to set and retrieve cookie values.
> 
> - Cookie options: React Cookies allows you to specify various options when setting cookies, such as the cookie's path, expiration date, domain, and security settings.
> 
> - Universal support: The library can be used in both client-side and server-side environments, enabling server-rendered React applications to handle cookies effectively.
> 
> - Lightweight: React Cookies is designed to be lightweight and has minimal dependencies, making it efficient and easy to integrate into your React projects.


**Which library would you prefer? Why?**
> I would prefer `react-cookies` because it provides a straightforward API for reading, writing, and removing cookies. It also supports server-side rendering and has cross-browser compatibility.