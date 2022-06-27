# Read: 07 - Bearer Authorization

## Reading

[Intro to JWT](https://jwt.io/introduction/)

1. **What is a JSON Web Token (JWT)?** JWT is an open standard that defines a compact and self-contained way for securely transmitting information between parties as a JSON object, can be verified and trusted.
2. **When should we use JSON Web Tokens?** JWTs are useful for authorization and information exchange. SSO uses JWT and allows the user to access routes, services, and resources that are permitted with the JWT.
3. **Claims are expected in which structural component of a JWT?** The payload contains the claims

[Are JWTs Secure?](https://stackoverflow.com/questions/27301557/if-you-can-decode-jwt-how-are-they-secure)

1. **If I get a JWT and I can decode the payload, how can we call that secure?** JWTs can be signed, encrypted, or both. If a token is not encrypted, but signed, anyone can read its contents, but if the private key isn't available then it cannot be changed because the signature does not match.
2. **If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.** Payload and secret
3. **Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.** When both parties know the secret, they can use hash functions to send and receive securely.

### Videos

[JWTs Explained](https://www.youtube.com/watch?v=926mknSW9Lo)

1. **Why use JWT?** To securely transfer data between any two bodies
2. **JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.** A single token contains information about the user, avoids querying the database more than once, and can easily be sent via URL, POST request, and HTTP Header.
3. **What are the three components (the structure) of a JWT signature?** Header, Payload, and Signature

### Bookmark and Review

[npm jsonwebtoken docs](https://www.npmjs.com/package/jsonwebtoken)