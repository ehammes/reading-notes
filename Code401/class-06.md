# Read: 06 - Authentication

## Reading

[Securing Passwords](https://thehackernews.com/2014/04/securing-passwords-with-bcrypt-hashing.html)

1. **Explain to a non-technical friend how you would safely hash and store a password.** An algorithm that stores plaintext passwords as hashes instead to represent the original password
2. **What is Bcrypt?** Bcrypt slows down brute force attacks - Bcrypt is an adaptive hash function based on the Blowfish symmetric block cipher cryptographic algorithm and introduces a work factor (security factor), which allows you to determine how expensive the hash function will be.
3. **Why might you use something like Bcrypt?** Minimize the impact of password breaches/hacks

[Basic Auth](https://en.wikipedia.org/wiki/Basic_access_authentication)

1. **What is Basic Authentication?** A method for an HTTP user agent (e.g. a web browser) to provide a user name and password when making a request.
2. **What properties are necessary in the header of a Basic Auth request?**  A request contains a header field in the form of Authorization: Basic `credentials`, where credentials are the Base64 encoding of ID and password joined by a single colon :.
3. **How are username:password in Basic Auth encoded?** Base64 encoding

[OWASP auth cheatsheet](https://www.owasp.org/index.php/Authentication_Cheat_Sheet)

1. **Define the authentication process to a non-technical recruiter.** Submitting a username or ID and one or more items of private information that only a given user should know.
2. **How should your error messaging respond (both HTTP and HTML)? Why?** Errors must respond with a generic error message without pinpointing the exact reason (user ID / password incorrect, account doesn't exist, etc.). If this information is provided, it can allow hackers to gather information about potential account information.
3. **Bookmark this link also and consider OWASP fundamentals any time you interact with authentication. Applications developed with security in mind from inception have fewer vulnerabilities throughout their lifecycle.**

### Bookmark and Review

[bcrypt docs](https://www.npmjs.com/package/bcrypt)