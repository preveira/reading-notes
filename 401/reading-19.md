# Reading-19 #

**What is the difference between SQS and SNS?**
The key difference between Amazon SQS (Simple Queue Service) and Amazon SNS (Simple Notification Service) is their messaging pattern. SQS is a message queuing service, facilitating communication between distributed application components by providing a reliable queue for storing and processing messages asynchronously. SNS, on the other hand, is a publish-subscribe (pub-sub) service, allowing a single message to be sent to multiple subscribers, such as email addresses, Lambda functions, or SQS queues. SQS is typically used for decoupling services and ensuring messages are processed in a reliable order, while SNS is used for broadcasting messages to multiple destinations.

**What are some use cases for both SNS and SQS?**
Some common use cases for SNS include:
- **Broadcasting Notifications:** Sending notifications to multiple subscribers, such as email, SMS, or mobile devices.
- **Fanout Messaging:** Distributing a message to multiple systems for processing.
- **Event-Driven Architecture:** Publishing events to trigger multiple reactions across a system.

For SQS, use cases include:
- **Task Queuing:** Queuing tasks for asynchronous processing by background workers.
- **Workload Distribution:** Balancing workload across multiple services or workers.
- **Error Handling:** Storing failed tasks for later reprocessing.

**Describe how to use SQS and SNS in a “fanout” pattern.**
The "fanout" pattern involves sending a single message to multiple destinations for parallel processing. To implement this pattern with SQS and SNS:
1. **Create an SNS Topic:** This acts as the central point where messages are published.
2. **Create SQS Queues:** Set up multiple SQS queues, each representing a destination where messages will be processed.
3. **Subscribe SQS Queues to the SNS Topic:** Link the SQS queues to the SNS topic, allowing the message to be "fanned out" to all subscribers when published.
4. **Publish to the SNS Topic:** Publish a message to the SNS topic, which then sends the message to all subscribed SQS queues for asynchronous processing.

**Explain how “push notifications” work, using SNS.**
Push notifications with SNS work by sending messages to devices or endpoints in real-time. Here's the general process:
1. **Create an SNS Topic:** Define a topic to represent the category of notifications.
2. **Set Up Endpoints:** Register endpoints like mobile devices, email addresses, or webhooks as subscribers to the topic.
3. **Publish Notifications to the SNS Topic:** When an event triggers a notification, publish the message to the SNS topic.
4. **Deliver the Notifications:** SNS sends the notification to all subscribed endpoints in real-time, ensuring immediate delivery to the intended recipients.

**How might a large-scale, distributed application make use of a Queue system like SQS?**
A large-scale, distributed application can use SQS to improve reliability and scalability in various ways:
- **Decoupling Services:** By using SQS, application components can communicate asynchronously, reducing dependencies and allowing each service to operate independently.
- **Workload Balancing:** SQS can distribute tasks among multiple worker instances, ensuring even processing and reducing bottlenecks.
- **Error Handling and Recovery:** SQS provides dead-letter queues to handle failed messages, allowing for reprocessing and error tracking.
- **Scalable Task Processing:** As load increases, additional workers can be added to process messages from the queue, providing scalability on demand.
- **Reliable Event Processing:** SQS guarantees message delivery, making it suitable for critical tasks that require at-least-once processing.

## Things I want to know more about ##
