# Read: 18 - AWS: API, Dynamo and Lambda

## Reading

[AWS API Gateway Overview](https://www.serverless.com/amazon-api-gateway)

1. **What is Amazon API Gateway?** Amazon API Gateway is a managed service that allows developers to define the HTTP endpoints of a REST API or a WebSocket API and connect those endpoints with the corresponding backend business logic. It also handles authentication, access control, monitoring, and tracing of API requests.
2. **Why is Amazon API Gateway an important part of the Serverless ecosystem?** Replaces the API servers with a managed serverless solution - triggers the execution of a Serverless function directly in response to an HTTP request. Within the Serverless ecosystem, API Gateway is the piece that ties together Serverless functions and API definitions.
3. **How does API Gateway integrate with other AWS services?** Direct integrations that can be configured in the API Gateway user interface for the following: Invoking an AWS Lambda function, Invoking another HTTP endpoint, with or without VPC Link, Making an HTTP call against the API of any AWS service that provides an HTTP API, Returning a mock response generated within API Gateway without calling out to other services.

[AWS API Gateway](https://aws.amazon.com/api-gateway/)

1. **What are the some benefits of using Amazon API Gateway?** Performance, cost saving, monitoring capabilities, security, efficiency
2. **What two API types might you choose from?** RESTful APIs, Websocket APIs

[AWS DynamoDB Guide](https://www.dynamodbguide.com/what-is-dynamo-db/)

1. **What is DynamoDB?** A hosted NoSQL database offered by AWS. Offers built-in security, continuous backups, automated multi-Region replication, in-memory caching, and data export tools.
2. **Under what circumstances would you recommend DynamoDB over MongoDB?** Already using AWS. Applications with large amounts of data

[AWS DynamoDB](https://aws.amazon.com/dynamodb/)

1. **Explain to a non-technical friend how DynamoDB works.** DynamoDB is a database that supports large amounts of data at scale that can be used to build applications.

[Dynamoose](https://dynamoosejs.com/getting_started/Introduction)

1. **What is Dynamoose?** A modeling tool for Amazon's DynamoDB
2. **What are some key features of Dynamoose?** Type safety, High level API, Easy to use syntax, Ability to transform data before saving or retrieving documents, Strict data modeling (validation, required attributes, etc.), Support for DynamoDB Transactions, Powerful Conditional/Filtering Support, Callback & Promise support
