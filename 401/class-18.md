# AWS: API, Dynamo and Lambda

[**AWS API Gateway Overview**](https://www.serverless.com/guides/amazon-api-gateway)

*What is Amazon API Gateway?*

A service that allows developers to define the HTTP endpoints of a REST API or WebSocket API and connect those endpoints with the backend business logic. API Gateway also handles authentication, access control, monitoring, and tracing API requests.

*Why is Amazon API Gateway an important part of the Serverless ecosystem?*

API Gateway replaces API servers and ties together Serverless functions and API definitions. You can trigger a serverless fucntion in response to an HTTP request.

*How does API Gateway integrate with other AWS services?*

API Gateway can:

- run Lambda functions to generate HTTP responses
- publish SNS notifications when an HTTP API endpoint is accessed
- provide authentication and authorization for your HTTP APIs.

[**AWS API Gateway**](https://aws.amazon.com/api-gateway/)

*What are the some benefits of using Amazon API Gateway?*

- Makes it easy for devs to create, publish, maintain, monitor and secure APIs at any scale
- Handles processing concurrent API calls
  - traffic management
  - CORS support
  - authorization and access control
  - throttling
  - monitoring
  - API version management

*What two API types might you choose from?*

- RESTful APIs
- WebSocket APIs

[**AWS DynamoDB Guide**](https://www.dynamodbguide.com/what-is-dynamo-db/)

*What is DynamoDB?*

AWS's NoSQL database

*Under what circumstances would you recommend DynamoDB over MongoDB?*

- Applications with large amounts of data and strict latency requirements
- With serverless applications already using AWS Lambda
- Data sets with simple, known access patterns

[**AWS DynamoDB**](https://aws.amazon.com/dynamodb/)

*Explain to a non-technical friend how DynamoDB works.*

DynamoDB is a managed, serverless, key-value NoSQL database. It secures data and integrates with other AWS services.

[**Dynamoose**](https://dynamoosejs.com/getting_started/Introduction/)

*What is Dynamoose?*

A modeling took for Amazon's DynamoDB.

*What are some key features of Dynamoose?*

- easy to use syntax
- ability to transform data before saving or retrieving documents
- strict data modeling
- powerful conditional/filtering support