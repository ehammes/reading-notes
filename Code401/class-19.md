# Read: 19 - AWS: Events

## Reading

[AWS SQS vs SNS](https://medium.com/awesome-cloud/aws-difference-between-sqs-and-sns-61a397bf76c5)

1. **What is the difference betweeen SQS and SNS?** SNS is a distributed publish-subscribe service and SQS is distributed queuing service. Amazon SNS is a fast, flexible, fully managed push notification service that lets you send individual messages or to bulk messages to large numbers of recipients. Amazon SQS is a fully managed message queuing service that enables you to decouple and scale microservices, distributed systems, and serverless applications.
2. **What are some use cases for both SNS and SQS?**
    * SNS: multiple subscribers, publish and consume batches of matches, process a message in multiple ways
    * SQS: only one subscriber needed, parallel asynchronous processing, a simple queue

[AWS SNS and SQS](https://www.youtube.com/watch?v=mXk0MNjlO7A)

1. **Describe how to use SQS and SNS in a “fanout” pattern.** Using SQS you can subscribe multiple queues to the same topic to replicate a message over multiple queues while SNS can publish multiple messages to a topic.
2. **Explain how “push notifications” work, using SNS.** When a specific event occurs it triggers the message to the endpoint

[SQS and SNS Basics](https://www.youtube.com/watch?v=UesxWuZMZqI)

1. **How might a large scale, distributed application make use of a Queue system like SQS?** Large scale apps can use SQS to decouple the processing logic to use a queue that manages the processing and protects from unexpected surges

### Bookmark and Review

[SNS Javascript SDK](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/SNS.html)

[SQS Javascript SDK](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/SQS.html)
