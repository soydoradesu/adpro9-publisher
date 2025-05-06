# Question
1. How much data your publisher program will send to the message broker in one run?
The publisher program is designed to send exactly 5 messages to the message broker each time it runs. This fixed batch of data simulates a controlled message flow for testing or demonstration purposes.

2. The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber program, what does it mean?
If both the publisher and subscriber connect using the same URL, amqp://guest:guest@localhost:5672, it means they are communicating through the same RabbitMQ broker instance running locally. This shared connection point ensures that messages published by the producer are routed to the intended consumer within the same messaging environment.

![alt text](image.png)

- The publisher sent 5 event to the message broker. 
![alt text](image-1.png)