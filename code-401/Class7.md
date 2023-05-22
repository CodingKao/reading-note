# Class 7 Bearer Authorization

#### Link to article: [Intro to JWT](https://jwt.io/introduction/)

#### Link to article: [Are JWTs Secure?](https://stackoverflow.com/questions/27301557/if-you-can-decode-jwt-how-are-they-secure)

#### Link to video: [JWTs Explained](https://www.youtube.com/watch?v=926mknSW9Lo)

***

**Bookmark**

#### Link to video: [npm jsonwebtoken docs](https://www.npmjs.com/package/jsonwebtoken)

***

## Intro to JWT

**What is a JSON Web Token (JWT)?**
> A JSON Web Token (JWT) is like a digital passport that securely carries information, allowing users to prove their identity and access protected resources.

**When should we use JSON Web Tokens?**
> We should use JSON Web Tokens (JWTs) when we want a secure and efficient way to authenticate and authorize users, and share information between different systems or services.

**Claims are expected in which structural component of a JWT?**
> Claims are expected to be found in the payload component of a JSON Web Token (JWT), which contains information about the user or additional data associated with the token.

## Are JWTs Secure?

**If I get a JWT and I can decode the payload, how can we call that secure?**
> Even if the payload of a JWT can be decoded, the security lies in the digital signature. Verifying the signature ensures the integrity and authenticity of the token, making it secure.

**If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.**
> When sending a JWT, both the sender and receiver must know a secret key that is appended in the signature. This key is used to verify the integrity of the token.

**Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.**
> To securely send and receive concatenated content and a secret, it's like sending a locked box. The secret is the key to unlock the box and ensure only the intended recipient can access the content.

## JWTs Explained

**Why use JWT?**
> JWT is used to safely share information between two parties. The digitally signed data is checked and trusted. It's also small and efficient.

**JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.**
> JWT being compact and self-contained means it's like a small, all-in-one package. It's easy to send, store, and use without needing extra things, making it convenient and efficient.

**What are the three components (the structure) of a JWT signature?**
> The structure of a JWT signature consists of three components: header, payload, and signature. They work together to securely encode and verify the information contained in the token.

## Reflection

**What are your learning goals after reading and reviewing the class README?**
> My learning goals are to gain a clear understanding of how JSON Web Tokens (JWTs) work, their purpose, and how they can be used for authentication and authorization in web applications.
