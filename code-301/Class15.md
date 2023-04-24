# Class 15 Authentication

#### Link to article: [What is OAuth](https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html)

#### Link to article: [Authorization and Authentication flows](https://auth0.com/docs/get-started/authentication-and-authorization-flow)

>

***

## What is OAuth

**What is OAuth?**
> OAuth is an authentication protocol that allows users to authorize third-party applications to access their resources without giving away their credentials.

**Give an example of what using OAuth would look like.** An example of using OAuth would be logging into a website using your Google or Facebook account instead of creating a new account specific to that website.

**How does OAuth work? What are the steps that it takes to authenticate the user?**
>
>- The user tries to access a protected resource on a website or app.
>
>- The website or app sends a request to an OAuth provider (like Google) for permission to access the user's data.
>
>- The OAuth provider prompts the user to grant or deny permission.
>
>- If permission is granted, the website or app receives an access token to access the user's data.
>
>- The website or app can then access the user's data using the access token.

**What is OpenID?**
> OpenID is an authentication protocol that allows users to use a single set of credentials to access multiple websites or applications.

***

## Authorization and Authentication flows

**What is the difference between authorization and authentication?**
> Authentication is the process of verifying a user's identity, while authorization is the process of determining what actions or resources the authenticated user is allowed to access.

**What is Authorization Code Flow?**
> Authorization Code Flow is an OAuth 2.0 flow that allows clients to request an authorization code from an authorization server, which can then be exchanged for an access token to access protected resources.

**What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?**
> Authorization Code Flow with Proof Key for Code Exchange (PKCE) is an extension to the Authorization Code Flow that adds an extra layer of security to prevent code interception attacks by sending a dynamically generated secret value with the authorization request.

**What is Implicit Flow with Form Post?**
> Implicit Flow with Form Post is an OAuth 2.0 flow that allows clients to obtain access tokens directly from the authorization endpoint, with the token being returned in the response body of a form POST request to the client's redirect URI.

**What is Client Credentials Flow?**
> Client Credentials Flow is an OAuth 2.0 flow that allows clients to authenticate and obtain an access token by presenting their client credentials (such as a client ID and secret) to the authorization server.

**What is Device Authorization Flow?**
> Device Authorization Flow is an OAuth 2.0 flow for devices with limited input capabilities to obtain user consent and an access token.

**What is Resource Owner Password Flow?**
> Resource Owner Password Flow is an OAuth 2.0 flow that allows clients to authenticate and obtain an access token by directly exchanging the user's credentials with the authorization server.
