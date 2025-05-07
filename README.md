# Aws2-SQS
https://www.youtube.com/watch?v=12CINbV4ptw&list=PLviC8AFqAj5CDH_e9k3idoBOBhVXC-WNm&index=23


https://medium.com/avmconsulting-blog/aws-sqs-aws-simple-queue-service-how-sqs-works-fc412837de8c


Amazon Simple Queue Service (SQS) is a fully managed message queuing service offered by AWS. It enables decoupling and scaling of microservices, distributed systems, and serverless applications.
Two Types of Queues:

Standard Queue: Offers best-effort ordering, at-least-once delivery, and nearly unlimited throughput. Standard queues provide high throughput and are suitable for most applications.
 (First-In-First-Out) Queue: Guarantees the order in which messages are sent and received and ensures exactly-once

 
 ![image](https://github.com/user-attachments/assets/7590a641-3b1c-4ad5-8fe0-ec182733e0c9)

 FIFO (First-In-First-Out) Queue: Guarantees the order in which messages are sent and received and ensures exactly-once processing. 
 FIFO queues are ideal for applications that require strict ordering and de-duplication of messages.
 ![image](https://github.com/user-attachments/assets/391129d0-bc3e-4c01-9365-b5ccd93c64e3)

Message Retention Period: SQS retains messages in the queue for a configurable period (from 1 minute to 14 days). If a message is not processed within this period, it becomes available for processing by another consumer.
Delete the messages using the Delete Message API.
