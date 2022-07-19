# AWS Events

[**AWS SQS vs SNS**](https://medium.com/awesome-cloud/aws-difference-between-sqs-and-sns-61a397bf76c5)

*What is the difference betweeen SQS and SNS?*

SNS is Amazon's Simple Notification Service - a push notification service that lets you send individual or bulk messages to recipients.

SQS is Amazon's Simple Queue Service - a distributed queuing system. Rather than pushing messages to receivers, receivers have to poll SQS to receive messages.

*What are some use cases for both SNS and SQS?*

SNS:

- the need to publish and consume batches of messages
- needing the same message processed in multiple ways
- multiple subscribers are needed

SQS:

- need a simple queue
- Decoupling two applications and allowing parallel asynchronous processing.
- Only one subscriber is needed.

[**AWS SNS and SQS**]

*Describe how to use SQS and SNS in a “fanout” pattern.*

An event occurs and an SNS topic then sends that payload to different services (could be SNS and/or SQS) that can process that information independently of each other.

*Explain how “push notifications” work, using SNS.*

When an event occurs messages are sent to all subscribers of that topic. For example, ordering something online. The order event occurs, an SNS will receive the payload then send an email confirming your order.

[**SQS and SNS Basics**]

*How might a large scale, distributed application make use of a Queue system like SQS?*

