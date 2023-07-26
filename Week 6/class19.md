# AWS: Events

----

**AWS SQS vs SNS**

What is the difference betweeen SQS and SNS?

> * Amazon SQS (Simple Queue Service) is a message queuing service used for decoupling components in a distributed system.
> * Amazon SNS (Simple Notification Service) is a pub/sub messaging service for broadcasting messages to multiple subscribers in real-time.

What are some use cases for both SNS and SQS?

> For SNS: 
> * Real-time notifications to multiple subscribers.
> * Mobile push notifications.

> For SQS: 
> * Task queues for decoupling.
> * Event sourcing and processing.
> * Microservices communication.


----

**AWS SNS and SQS**

Describe how to use SQS and SNS in a “fanout” pattern.

> In a "fanout" pattern: you first create an SNS topic and then multiple SQS queues, with one queue per subscriber. Next, subscribe each SQS queue to the SNS topic. When you publish messages to the SNS topic, the messages will be automatically distributed to all the subscribed SQS queues. Each subscriber (SQS queue) can then independently process the messages it receives.

Explain how “push notifications” work, using SNS.

> Amazon SNS enables push notifications to mobile devices and web browsers. Create platform applications for each platform, create an SNS topic, subscribe devices, and publish messages for delivery. SNS handles the rest, ensuring real-time notifications reach all subscribed devices.

----

**SQS and SNS Basics**

How might a large scale, distributed application make use of a Queue system like SQS?

> SQS is used in large distributed applications for reliable communication between components, load balancing, and fault tolerance. It enables asynchronous communication and helps the application scale effectively by handling varying workloads.