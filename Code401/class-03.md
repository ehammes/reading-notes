# Read: 03 - Express REST API

## Reading

[Review: ES6 Classes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)

1. **Classes are a template for creating ____.** Objects
2. **Can a class declaration be hoisted?** No, classes must be defined before they can be constructed.
3. **How would you describe a constructor and contextual “this” to a non-technical friend?** A constructor creates an object and and uses "this" to define the properties of the object/data

[Using Express Routing](https://expressjs.com/en/guide/routing.html)

1. **Within Express, what does routing refer to?** Routing refers to how an application's endpoints (URIs) responds to client requests
2. **What is the difference between a route path and a route method?** A route method is derived from one of the HTTP methods, and is attached to an instance of the express class. Route paths define the endpoints at which requests can be made. Route paths can be strings, string patterns, or regular expressions.
3. **When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?** Use next when there are multiple callback functions to handle a request. This can be used to impose preconditions on a route, then pass control to subsequent routes if there's no reason to proceed with the current route

[Express Routing](https://scotch.io/tutorials/learn-to-use-the-new-router-in-expressjs-4)

1. **What is an Express Router?** An express router only includes routing info and allows applications to be more modular and flexible by creating multiple instances of the Router and applying them accordingly.
2. **By what mean do we initialize express.Router() in an express server?** Call an instance of router, apply routes to it, and then tell the application to use the routes. Can be used for basic routes, authenticated routes, and API routes.
3. **What do we use route middleware for?** Route middleware is used to do a specific action before a request is processed - such as checking if a user is authenticated or logging data for analytics.
