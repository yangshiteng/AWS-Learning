# Coursera - AWS Cloud Practitioner Essentials

Amazon Web Services (AWS) is the world’s most comprehensive and broadly adopted cloud platform, offering over 200 fully featured services from data centers globally. If you are a developer new to AWS, this is where you can learn to build applications on AWS. Choose the programming language and tools familiar to you, learn about core concepts applicable across any service you end up using, and then go build!

## Week 1

- Amazon Elastic Compute Cloud (Amazon EC2) (弹性云计算)
- Pay for what you need
- AWS Certified Cloud Practitioner exam

### What is Cloud Computing?

Cloud Computing is the on-demand delivery of IT resources (按需求交付IT资源) over the internet with pay-as-you-go pricing

Instead of buying, owning, and maintaining physical data centers and servers, you can access technology services, such as computing power, storage, and databases, on an as-needed basis from a cloud provider like Amazon Web Services (AWS).

### Who is using cloud computing?

Organizations of every type, size, and industry are using the cloud for a wide variety of use cases, such as data backup, disaster recovery, email, virtual desktops, software development and testing, big data analytics, and customer-facing web applications. For example, healthcare companies are using the cloud to develop more personalized treatments for patients. Financial services companies are using the cloud to power real-time fraud detection and prevention. And video game makers are using the cloud to deliver online games to millions of players around the world.

### What is a Client-Server Model?

In computing, a client can be a web browser or desktop application that a person interacts with to make requests to computer servers. A server can be services such as Amazon Elastic Compute Cloud (Amazon EC2), a type of virtual server.

For example, suppose that a client makes a request for a news article, the score in an online game, or a funny video. The server evaluates the details of this request and fulfills it by returning the information to the client.

### Deployment Models for Cloud Computing

The three cloud computing deployment models are cloud-based, on-premises, and hybrid.

![image](https://user-images.githubusercontent.com/60442877/155901467-d5b1afef-b486-4097-a090-af24685c0758.png)
![image](https://user-images.githubusercontent.com/60442877/155901473-987dba38-2984-4de8-b4ab-78cffb356063.png)
![image](https://user-images.githubusercontent.com/60442877/155901557-e856299c-f147-448f-b49e-343353f0c409.png)

### Benefits of Cloud Computing

- Upfront expense： refers to data centers, physical servers, and other resources that you would need to invest in before using them.
- Variable expense: you only pay for computing resources you consume instead of investing heavily in data centers and servers before you know how you’re going to use them.
![image](https://user-images.githubusercontent.com/60442877/155901745-5feb3be7-9bb5-4c4e-896e-e39354d401c4.png)
![image](https://user-images.githubusercontent.com/60442877/155901765-d11e2815-bb69-4993-957d-e3d481e9cfc9.png)
![image](https://user-images.githubusercontent.com/60442877/155901819-d28d3f04-3177-4fc4-a7d5-7b702745a344.png)
![image](https://user-images.githubusercontent.com/60442877/155901868-5c7e2987-7fbf-4467-a192-2b8e4e66b208.png)
![image](https://user-images.githubusercontent.com/60442877/155901908-1638314f-1541-40fb-9d80-3e5b16d77d47.png)
![image](https://user-images.githubusercontent.com/60442877/155901956-d01d1919-2149-4cda-9b97-317f6025bfe4.png)

### Types of Cloud Computing

There are three main models for cloud computing. Each model represents a different part of the cloud computing stack.

1. Infrastructure as a Service (IaaS)
2. Platform as a Service (PaaS)
3. Software as a Service (SaaS)

![image](https://user-images.githubusercontent.com/60442877/155902460-f3f9891d-8eea-47a3-b956-4f99bda33dde.png)

### Amazon Elastic Compute Cloud (Amazon EC2)

- Multitenancy: sharing underlying hardware between virtual machines 
- provides secure, resizable compute capacity in the cloud as Amazon EC2 instances. 
![image](https://user-images.githubusercontent.com/60442877/155903086-8251e4e2-5692-4947-b5ca-7b7cd684b65f.png)

### How Amazon EC2 works

![image](https://user-images.githubusercontent.com/60442877/155903103-2bd6831f-e736-40de-a903-f63967efb884.png)

### Amazon EC2 instance types

When selecting an instance type, consider the specific needs of your workloads and applications. This might include requirements for compute, memory, or storage capabilities.

![image](https://user-images.githubusercontent.com/60442877/155904924-ddd86719-890e-4cbf-bf1b-b7f6295024ce.png)
![image](https://user-images.githubusercontent.com/60442877/155905028-f09056a2-1b95-4057-9016-9dc649a89789.png)
![image](https://user-images.githubusercontent.com/60442877/155905101-2536c597-4662-4dab-a01e-411d6251c183.png)
![image](https://user-images.githubusercontent.com/60442877/155905147-53a9afad-3f86-4b78-b838-94cfa0bef3a0.png)
![image](https://user-images.githubusercontent.com/60442877/155905270-86a8670f-df2a-4a26-9a72-fec430ac9024.png)

### Amazon EC2 Pricing

With Amazon EC2, you pay only for the compute time that you use. Amazon EC2 offers a variety of pricing options for different use cases. For example, if your use case can withstand interruptions, you can save with Spot Instances. You can also save by committing early and locking in a minimum level of use with Reserved Instances.

![image](https://user-images.githubusercontent.com/60442877/155905603-dcd63af8-456f-4b00-bdeb-458fc6aaa43f.png)
![image](https://user-images.githubusercontent.com/60442877/155905785-4f5fde4a-ed00-4228-9ec8-66935348669b.png)
![image](https://user-images.githubusercontent.com/60442877/155905835-830d4dfa-7d19-4163-b0cf-92cc1f653040.png)
![image](https://user-images.githubusercontent.com/60442877/155906285-c6732dae-2a36-4333-bb1d-82a0c93c9625.png)


### Scaling Amazon EC2

![image](https://user-images.githubusercontent.com/60442877/155906665-14cf7cc3-b945-43d4-b42b-d27c74039e2b.png)

Amazon EC2 Auto Scaling: If you’ve tried to access a website that wouldn’t load and frequently timed out, the website might have received more requests than it was able to handle. This situation is similar to waiting in a long line at a coffee shop, when there is only one barista present to take orders from customers.

Amazon EC2 Auto Scaling enables you to automatically add or remove Amazon EC2 instances in response to changing application demand. By automatically scaling your instances in and out as needed, you are able to maintain a greater sense of application availability.

![image](https://user-images.githubusercontent.com/60442877/155906819-50d47ac7-66da-4dae-b3de-89fda4d3f852.png)

In the cloud, computing power is a programmatic resource, so you can take a more flexible approach to the issue of scaling. By adding Amazon EC2 Auto Scaling to an application, you can add new instances to the application when necessary and terminate them when no longer needed.

Suppose that you are preparing to launch an application on Amazon EC2 instances. When configuring the size of your Auto Scaling group, you might set the minimum number of Amazon EC2 instances at one. This means that at all times, there must be at least one Amazon EC2 instance running.

![image](https://user-images.githubusercontent.com/60442877/155907210-fac4308b-b0c4-4210-81c7-2d37001fc446.png)

![image](https://user-images.githubusercontent.com/60442877/155907251-9b2c0ba4-8797-4a1c-a857-1360568535d4.png)

### Elastic Load Balancer (弹性负载均衡器)

Elastic Load Balancing is the AWS service that automatically distributes incoming application traffic across multiple resources, such as Amazon EC2 instances. 

A load balancer acts as a single point of contact for all incoming web traffic to your Auto Scaling group. This means that as you add or remove Amazon EC2 instances in response to the amount of incoming traffic, these requests route to the load balancer first. Then, the requests spread across multiple resources that will handle them. For example, if you have multiple Amazon EC2 instances, Elastic Load Balancing distributes the workload across the multiple instances so that no single instance has to carry the bulk of it. 

Although Elastic Load Balancing and Amazon EC2 Auto Scaling are separate services, they work together to help ensure that applications running in Amazon EC2 can provide high performance and availability. 

![image](https://user-images.githubusercontent.com/60442877/155910646-b9fde18b-c1e9-4111-bed9-7d7e58037768.png)
![image](https://user-images.githubusercontent.com/60442877/155910655-3585bac6-6f25-4abb-8405-e464df54e1af.png)
![image](https://user-images.githubusercontent.com/60442877/155910670-a1342f9a-5220-4431-bb7a-b2172804e4cd.png)


### Messaging and Queueing

- Tightly Coupled Architecture
- Loosely Coupled Architecture: single failure won't cause cascading failures

Loosely Coupled Architecture:
1. Amazon Simple Queue Service (Amazon SQS) 亚马逊简单队列服务
2. Amazon Simple Notification Service (Amazon SNS) Amazon简单通知服务

Monolithic Applications(整体应用程序):

Applications are made of multiple components. The components communicate with each other to transmit data, fulfill requests, and keep the application running. 

Suppose that you have an application with tightly coupled components. These components might include databases, servers, the user interface, business logic, and so on. This type of architecture can be considered a monolithic application. 

In this approach to application architecture, if a single component fails, other components fail, and possibly the entire application fails.

Microservices:

To help maintain application availability when a single component fails, you can design your application through a microservices approach.

In a microservices approach, application components are loosely coupled. In this case, if a single component fails, the other components continue to work because they are communicating with each other. The loose coupling prevents the entire application from failing. 

When designing applications on AWS, you can take a microservices approach with services and components that fulfill different functions. Two services facilitate application integration: Amazon Simple Notification Service (Amazon SNS) and Amazon Simple Queue Service (Amazon SQS).

### Amazon Simple Notification Service (Amazon SNS)

Amazon Simple Notification Service (Amazon SNS) is a publish/subscribe service. Using Amazon SNS topics, a publisher publishes messages to subscribers. This is similar to the coffee shop; the cashier provides coffee orders to the barista who makes the drinks.

In Amazon SNS, subscribers can be web servers, email addresses, AWS Lambda functions, or several other options. 

![image](https://user-images.githubusercontent.com/60442877/155915681-7b1e9175-9479-4273-9277-7802e2558b66.png)
![image](https://user-images.githubusercontent.com/60442877/155915697-80b0c382-1480-47cd-a84a-7eb3b73c2d2d.png)

### Amazon Simple Queue Service (Amazon SQS)

Amazon Simple Queue Service (Amazon SQS) is a message queuing service. 

Using Amazon SQS, you can send, store, and receive messages between software components, without losing messages or requiring other services to be available. In Amazon SQS, an application sends messages into a queue. A user or service retrieves a message from the queue, processes it, and then deletes it from the queue.

![image](https://user-images.githubusercontent.com/60442877/155917991-383dacd0-5771-43d5-8878-00feef8c6f87.png)

Suppose that the coffee shop has an ordering process in which a cashier takes orders, and a barista makes the orders. Think of the cashier and the barista as two separate components of an application. 

First, the cashier takes an order and writes it down on a piece of paper. Next, the cashier delivers the paper to the barista. Finally, the barista makes the drink and gives it to the customer.

When the next order comes in, the process repeats. This process runs smoothly as long as both the cashier and the barista are coordinated.

What might happen if the cashier took an order and went to deliver it to the barista, but the barista was out on a break or busy with another order? The cashier would need to wait until the barista is ready to accept the order. This would cause delays in the ordering process and require customers to wait longer to receive their orders.

As the coffee shop has become more popular and the ordering line is moving more slowly, the owners notice that the current ordering process is time consuming and inefficient. They decide to try a different approach that uses a queue.

![image](https://user-images.githubusercontent.com/60442877/155918006-239b89a5-d2ac-4d86-90cf-839caa4c5285.png)

Recall that the cashier and the barista are two separate components of an application. A message queuing service such as Amazon SQS enables messages between decoupled application components.

In this example, the first step in the process remains the same as before: a customer places an order with the cashier. 

The cashier puts the order into a queue. You can think of this as an order board that serves as a buffer between the cashier and the barista. Even if the barista is out on a break or busy with another order, the cashier can continue placing new orders into the queue. 

Next, the barista checks the queue and retrieves the order.

The barista prepares the drink and gives it to the customer. 

The barista then removes the completed order from the queue. 

While the barista is preparing the drink, the cashier is able to continue taking new orders and add them to the queue.

### Serverless Computing

- An AWS service for serverless computing is AWS Lambda
- AWS Lambda is a service that lets you run code without needing to provision or manage servers. 

![image](https://user-images.githubusercontent.com/60442877/155920501-609e8d59-4f9f-47c5-85e4-ccb41c7c7905.png)
![image](https://user-images.githubusercontent.com/60442877/155920538-d7cec4b5-f385-46ad-894f-f60f3b3b8ef9.png)
![image](https://user-images.githubusercontent.com/60442877/155920594-bcc39b38-ca24-4353-837e-54ad9fbd4d3e.png)
![image](https://user-images.githubusercontent.com/60442877/155920605-cdf832af-f958-45a2-84df-ef18802b9431.png)
![image](https://user-images.githubusercontent.com/60442877/155920636-098dd0e6-ad8a-4d90-847c-9f047ce73974.png)


### AWS Computer Services

https://aws.amazon.com/products/compute/
https://docs.aws.amazon.com/whitepapers/latest/aws-overview/compute-services.html

![image](https://user-images.githubusercontent.com/60442877/155921580-b59f13f5-3c50-4422-a85e-e2d648179119.png)
