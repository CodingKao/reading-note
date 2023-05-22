# Class 6 Data Modeling

#### Link to article: [Securing Passwords](https://thehackernews.com/2014/04/securing-passwords-with-bcrypt-hashing.html)

#### Link to article: [Basic Auth](https://en.wikipedia.org/wiki/Basic_access_authentication)

#### Link to article: [OWASP auth cheatsheet](https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html)

***

**Bookmark**

#### Link to video: [bcrypt docs](https://www.npmjs.com/package/bcrypt)

***

## Securing Passwords

**Explain to a non-technical friend how you would safely hash and store a password.**
> To keep passwords safe, we use a special function called Bcrypt to convert them into unreadable codes before storing them securely.

**What is Bcrypt?**
> Bcrypt is a special tool that transforms passwords into secret codes, making them difficult for others to understand or guess.

**Why might you use something like Bcrypt?**
> We use Bcrypt to make passwords very secure by turning them into secret codes that are hard for others to figure out, helping to protect our accounts and information.

## Basic Auth

**What is Basic Authentication?**
> Basic Authentication is a simple way to protect access to a website or system by requiring a username and password to verify the identity of the user.

**What properties are necessary in the header of a Basic Auth request?**
> In the header of a Basic Auth request, the "Authorization" property is necessary, which includes the word "Basic" followed by the encoded username:password combination.

**How are `username:password` in Basic Auth encoded?**
> In Basic Authentication, the username:password combination is encoded using Base64, which is a way to convert data into a format that can be safely transmitted over the internet.

## OWASP auth cheatsheet

**Define the authentication process to a non-technical recruiter.**
> The authentication process is like showing an ID to prove who you are. You provide your username and password to access a system or website, and it checks if they match to grant you access.

**How should your error messaging respond (both HTTP and HTML)? Why?**
> Error messages should be vague to prevent attackers from knowing specific details. Using generic messages for both HTTP responses and HTML pages helps maintain security and protect sensitive information.

## Reflection

**Looking ahead at this module’s course schedule, What do you look forward to learning?**
> I look forward to learning how different types of authentication, like basic and bearer, and role-based access control work to secure systems and control user access.

**What are your learning goals after reading and reviewing the class README?**
> After reading the class README, my learning goals are to understand how basic authentication, bearer authentication, and role-based access control can be used to secure systems and manage user permissions effectively.
