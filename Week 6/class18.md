# AWS: API, Dynamo and Lambda

----

**AWS API Gateway Overview**

1. What is Amazon API Gateway?

> Is a managed service that allows developers to define the HTTP endpoints of a REST API or a WebSocket API and connect those endpoints with the corresponding backend business logic. It also handles authentication, access control, monitoring, and tracing of API requests.


2. Why is Amazon API Gateway an important part of the Serverless ecosystem?

> Within the Serverless ecosystem, API Gateway is the piece that ties together Serverless functions and API definitions. Being able to trigger the execution of a Serverless function directly in response to an HTTP request is the key reason why API Gateway is so valuable in Serverless setups: it enables a truly serverless architecture for web applications. 


3. How does API Gateway integrate with other AWS services?

> Amazon API Gateway integrates with AWS Lambda, S3, DynamoDB, Step Functions, Cognito, IAM, Kinesis, SNS, and SQS, enabling powerful API interactions with various AWS services.

----

**AWS API Gateway**

What are the some benefits of using Amazon API Gateway?

> Lead to reduced time-to-market for new HTTP APIs, increased developer productivity, and the ability to maintain scalable solutions for your application development.

What two API types might you choose from?

>* REST APIs
>* WebSocket APIs


----

**AWS DynamoDB Guide**

What is DynamoDB?

> Is a hosted NoSQL database offered by Amazon Web Services (AWS). 

Under what circumstances would you recommend DynamoDB over MongoDB?

> Use DynamoDB when you need predictable performance, automatic scaling, and a simplified data model in a serverless environment.

----

**AWS DynamoDB**

Explain to a non-technical friend how DynamoDB works.

> Think of DynamoDB as a high-tech storage box for your data. It can hold a lot of information and quickly find exactly what you need. It's like having a super-fast and organized digital filing system for all your important stuff. No matter how much data you have, DynamoDB can handle it effortlessly.


----

**Dynamoose**

What is Dynamoose?

>  Is a modeling tool for Amazon's DynamoDB

What are some key features of Dynamoose?

> * Type safety
> * High level API
> * Easy to use syntax