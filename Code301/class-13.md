# Read: 13 - More CRUD

## Reading

### [CRUD Basics](https://medium.com/geekculture/crud-operations-explained-2a44096e9c88)

- **Which HTTP method would you use to update a record through an API?** After retrieving data (READ), then the data can be updated (UPDATE) using a PUT request - this replaces all current data of the target resource with the uploaded content.
- **Which REST methods require an ID parameter?** The PUT REST method requires an ID parameter to target the data to update. DELETE requires a unique id in the request in order to remove specific data from the database.

#### [Speed Coding: Building a CRUD API](https://www.youtube.com/watch?v=EzNcBhSv1Wo)

- **What’s the relationship between REST and CRUD?** Using REST applications involves CRUD functions and data in REST applications can be Created, Read, Updated, and Deleted. CRUD maps to the HTTP methods used by REST APIs- GET, POST, DELETE, PUT, and PATCH
- **If you had to describe the process of creating a RESTful API in 5 steps, what would they be?**
  1. Initialize and configure needed modules and packages. Add all the necessary items to the server.js file - what is required, needs to be used, the routes, any error handling
  2. Specifically for routes - Create GET request(s) to read data, POST request to create data, PUT request to update data, and DELETE to remove data from the db
  3. Create .env file and define the port
  4. Setup and connect database (ie MongoDB) to store data
  5. Verify that the requests and responses are working as expected between the server and database
