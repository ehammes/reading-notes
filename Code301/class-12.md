# Read: 12 - CRUD

## Reading

### [Status Codes Based On REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)

- **In your own words, describe what each group of status code represents:**
  - 100’s = informational status codes
  - 200’s = success codes
  - 300’s = redirection codes, the resource that is being requested is no longer avilable at the expected location
  - 400’s = client error codes, invalid requests a client sent to a server
  - 500’s = server error codes
- **What is a status code 202?** met all validation requirements at the time of sending
- **What is a status code 308?** Permanent redirect - tells the client to use another URL to access the resource and no longer use the current URL
- **What code would you use if an update didn’t return data to a client?** 204 No Content
- **What code would you use if a resource used to exist but no longer does?** 410 Gone
- **What is the ‘Forbidden’ status code?** 403 Forbidden

#### [Build A REST API With Node.js, Express, & MongoDB - Quick](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw)

- **Why do we need to pull our MongoDB database string out of our server and put it into our .env?** So that we can use the correct URL instead of localhost
- **What is middleware?** Code that runs when the server gets a request, but before it gets passed to our routes.
- **What does `app.use(express.json())` do?** Allows our server to accept json
- **What does the /:id mean in a route?** That it is a parameter
- **What is the difference between PUT and PATCH?** PUT - updates all information at once, PATCH - only updates what the user passes
- **How do you make a default value in a schema?** set a value to 'default' (ie. `default: Date.now`)
- **What does a 500 error status code mean?** An error failure with the server
- **What is the difference between a status 200 and a status 201?** 201 means something was successfully created and 200 means everything was successful
