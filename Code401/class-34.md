# Read: 34 - API Integration

## Reading

[Review API Server Build](https://codefellows.github.io/code-401-javascript-guide/curriculum/apps-and-libraries/api-server/)

1. **Explain the different between a query string parameter and a path parameter.** query string parameters define specifics about a path, ie `category=electronics` in  http://amazingapi.com/api/v1/products?category=electronics
2. **What would our API URL with a path id parameter be given the following information:**
    1. Domain: http://our-site.com
    2. v3
    3. model name: stuff
    4. id: things
    http://our-site.com/api/v3/stuff/things
3. **We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend.** A common interface provides the means to intake data

[Review Auth Server Build](https://codefellows.github.io/code-401-javascript-guide/curriculum/apps-and-libraries/auth-server/)

1. **Describe how you would use middleware to implement basic and bearer auth.** Middleware helps validate the user based on headers in the request
2. **Describe the handshake necessary to implement OAuth.** The OAuth processes is initiated in the browser, using a 3rd party authentication/authorization service. It will invoke a GET on the /oauth route. The OAuth middleware completes the handshaking process, create/update a local user account in the database, and returns an object with a re-authentication/bearer token and the user object.
3. **Describe how Role Based Access Control works to a non-technical friend.** RBAC is defined by each organization depending on the roles and responsibilities of the company. Each user is assigned a role based on their job and the role has specific access rights and permissions that they can perform.
