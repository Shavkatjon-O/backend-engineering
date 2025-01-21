# Backend Communication Design Patterns

### Resources:
- [ByteByteGo - Top 6 Most Popular API Architecture Styles ](https://youtu.be/4vLxWqE94l4?si=Su67NzWuujOjL3zX)

### Notes:

**Backend communication design patterns** are strategies or best practices for structuring how different parts of a backend system communicate with each other or with other systems. These patterns ensure efficient, scalable, and maintainable communication. Some common patterns include:

1. **Request-Response**: A client sends a request to a server, and the server responds. (e.g., REST APIs, GraphQL).

2. **Event-Driven**: Components communicate by emitting and listening to events. Useful for real-time updates or loosely-coupled systems.

3. **Pub-Sub (Publish-Subscribe)**: A publisher sends messages to a topic or channel, and subscribers receive those messages without direct knowledge of the publisher.

4. **Message Queues**: Messages are sent to a queue (e.g., RabbitMQ, Kafka) and processed asynchronously by workers, useful for decoupling and load handling.

5. **WebSockets/Server-Sent Events**: Persistent connections for real-time, bidirectional communication, commonly used in chat apps and live notifications.

6. **Service-Oriented/Remote Procedure Calls (RPC)**: Services communicate by invoking methods on each other (e.g., gRPC, Thrift).

Each pattern suits specific use cases depending on the system's requirements, such as scalability, real-time processing, or fault tolerance.