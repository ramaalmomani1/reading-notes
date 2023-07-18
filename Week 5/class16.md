# AWS: Cloud Servers


**AWS EC2**

1. What is an EC2 Instance?

> An EC2 instance is a virtual server provided by Amazon Web Services (AWS). It allows you to rent computer resources in the cloud. EC2 instances are flexible, scalable, and secure. They are commonly used for hosting websites, running applications, and performing various computing tasks in the cloud.

2. Name 2 use cases for EC2.

> * Web Hosting 
> * mApplication Development and Testing

3. Provide 1 reason to use ECS instead of a service such as Heroku, Digital Ocean, or Render.com.

> Its seamless integration with other Amazon Web Services (AWS). This integration allows you to leverage a wide range of AWS services, such as managed databases, storage, content delivery, and security, to build a comprehensive and scalable infrastructure for your application

----

**EC2 For Humans**

1. Where can we find EC2 on the AWS Console?

> Compute section

2. Explain the general difference between T2 Micro and XL.

> T2 Micro instances have lower performance and capacity, suitable for lightweight workloads. T2 XL instances have higher performance and capacity, ideal for heavier workloads. T2 Micro is more cost-effective, while T2 XL has higher pricing.

3. Explain a “Compute Cycle” to a non-technical friend.

> A compute cycle is like a single action a computer takes to do something. For example, when you click a mouse to open a program, the computer goes through a compute cycle. It fetches the instructions for opening the program, processes them, and shows the program on the screen. Each click represents one compute cycle, and the computer does many cycles quickly to complete tasks and run programs.

----

**Elastic Beanstalk**

1. What is Elastic Beanstalk?

> Is a service provided by Amazon Web Services (AWS) that simplifies the process of deploying and managing applications in the cloud. 

2. Describe the relationship between EC2 and Elastic Beanstalk.

> EC2 (Elastic Compute Cloud) and Elastic Beanstalk work together to deploy and manage applications in the AWS cloud. EC2 provides the virtual servers, known as instances, where your application runs. Elastic Beanstalk simplifies the process by abstracting away the infrastructure details and automating the provisioning and management of resources like EC2 instances. 

3. Name some benefits of using Elastic Beanstalk.

> Elastic Beanstalk makes deploying and managing applications in the cloud easy, helps your application scale, integrates with other AWS services, and allows customization to fit your needs