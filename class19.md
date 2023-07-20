# User

What is the difference betweeen SQS and SNS?

- SQS is a message queue service for asynchronous communication.
- SNS is a publish/subscribe messaging service for real-time message distribution.

What are some use cases for both SNS and SQS?

- Use cases for SNS: Push notifications, event notifications, fan-out scenarios.
- Use cases for SQS: Decoupling components, task queues, temporary message storage.

## AWS SNS and SQS

Describe how to use SQS and SNS in a “fanout” pattern.

- Fanout pattern: SNS broadcasts messages to multiple SQS queues.

Explain how “push notifications” work, using SNS.

- Real-time messages sent to subscribed endpoints.

### SQS and SNS Basics

How might a large scale, distributed application make use of a Queue system like SQS?

- Efficiently manages messaging between microservices for scalability.

| Home Page               | [Home Page](./README.md)                                |
