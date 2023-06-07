# Class 19: AWS: Events

#### Link to article: [AWS SQS vs SNS](https://medium.com/awesome-cloud/aws-difference-between-sqs-and-sns-61a397bf76c5)

#### Link to video: [AWS SNS and SQS](https://www.youtube.com/watch?v=mXk0MNjlO7A)

#### Link to video: [SQS and SNS Basics](https://www.youtube.com/watch?v=UesxWuZMZqI)



***

**Bookmarks**

#### Link to article: [SNS Javascript SDK](https://www.youtube.com/watch?v=yIVXjl4SwVo)

#### Link to article: [SQS Javascript SDK](https://www.youtube.com/watch?v=l0DfHUWMjsU)

***

## AWS SQS vs SNS

**What is the difference betweeen SQS and SNS?**
> SQS is a message queue for storing messages, while SNS is a pub/sub system for sending messages to multiple subscribers.

**What are some use cases for both SNS and SQS?**
> Use SQS when you need to decouple components and handle high volumes of messages, and SNS for fan-out messaging to multiple subscribers.


## AWS SNS and SQS

**Describe how to use SQS and SNS in a “fanout” pattern.**
> In a fanout pattern, publish messages to an SNS topic, and subscribers (like SQS queues) will automatically receive copies of each message for processing.

**Explain how “push notifications” work, using SNS.**
> With SNS, applications can subscribe to a topic, and when an event occurs, SNS sends push notifications to all subscribed endpoints, delivering relevant information instantly.

## SQS and SNS Basics

**How might a large scale, distributed application make use of a Queue system like SQS?**
> A large-scale distributed application can use SQS to decouple components, handle high message volumes, and ensure reliable message processing and coordination among various parts of the application.



## Reflection

**What are your learning goals after reading and reviewing the class README?**
> Looking forward to learning more about the difference between SNS and SQS, FIFO queues, publisher/subscriber relationships and how to apply these concepts in an application. 