# Microservices
- [способы коммуникации между микросервисами?](#способы-коммуникации-между-микросервисами)
- [exchange в message queue?](#exchange-в-message-queue)
- [в чем плюсы микросервисов?](#в-чем-плюсы-микросервисов)
- [минусы микросервисов?](#минусы-микросервисов)
- [В микросервисах какие могут быть проблемы?](#в-микросервисах-какие-могут-быть-проблемы)
- [как решается проблема с коммуникацией, когда какой-либо сервис не доступен?](#как-решается-проблема-с-коммуникацией-когда-какой-либо-сервис-не-доступен)
- [что такое rabbitMQ?](#что-такое-rabbitmq)
- [асинхронный vs синхронный вид коммуникации?](#асинхронный-vs-синхронный-вид-коммуникации)
- [возможные решениея для реализации аутентификации в микросервисной архитектуре?](#возможные-решениея-для-реализации-аутентификации-в-микросервисной-архитектуре)

## способы коммуникации между микросервисами?
+ Synchronous protocol. HTTP is a synchronous protocol. The client sends a request and waits for a response from the service. That's independent of the client code execution that could be synchronous (thread is blocked) or asynchronous (thread isn't blocked, and the response will reach a callback eventually). The important point here is that the protocol (HTTP/HTTPS) is synchronous and the client code can only continue its task when it receives the HTTP server response.
+ Asynchronous protocol. Other protocols like AMQP (a protocol supported by many operating systems and cloud environments) use asynchronous messages. The client code or message sender usually doesn't wait for a response. It just sends the message as when sending a message to a RabbitMQ queue or any other message broker.
###### Relative links:
+ https://docs.microsoft.com/en-us/dotnet/architecture/microservices/architect-microservice-container-applications/communication-in-microservice-architecture
+ https://dzone.com/articles/communication-between-microservices

## exchange в message queue?
Exchange: a queue aggregator that abstract away message queues and routes messages to the appropriate queue based on some predefined logic.
###### Relative links:
+ https://dev.to/matteojoliveau/microservices-communications-why-you-should-switch-to-message-queues--48ia

## в чем плюсы микросервисов?
+ Technology Heterogeneity
+ Resilience
+ Scaling
+ Ease of Deployment
+ Organizational Alignment
+ Composability
+ Optimizing for Replaceability
###### Relative links:
+ https://stackoverflow.com/questions/34903605/microservices-what-are-pros-and-cons
+ https://www.tiempodev.com/blog/disadvantages-of-a-microservices-architecture/

## минусы микросервисов?
+ Microservices Are More Complex
+ Microservices Require Cultural Changes
+ Microservices Are More Expensive
+ Microservices Pose Security Challenges
###### Relative links:
https://www.tiempodev.com/blog/disadvantages-of-a-microservices-architecture/

## В микросервисах какие могут быть проблемы?
1. As if monitoring a monolith wasn’t hard enough
2. Logging is distributed between services
3. An issue that’s caused by one service, can cause trouble elsewhere
4. Finding the root cause of problems
5. Version management and cyclic dependencies between services
###### Relative links:
+ https://blog.overops.com/5-ways-to-not-f-up-your-microservices-in-production/

## как решается проблема с коммуникацией, когда какой-либо сервис не доступен?
1. The circuit breaker pattern is the solution to this problem. The basic idea behind the circuit breaker is very simple. You wrap a protected function call in a circuit breaker object, which monitors for failures. Once the failures reach a certain threshold, the circuit breaker trips, and all further calls to the circuit breaker return with an error or with some alternative service or default message, without the protected call being made at all. This will make sure system is responsive and threads are not waiting for an unresponsive call.
2. Retry Logic
###### Relative links:
+ https://blog.risingstack.com/designing-microservices-architecture-for-failure/
+ https://dzone.com/articles/circuit-breaker-pattern

## что такое rabbitMQ?
RabbitMQ, also known as Open-Source Message Broker, supports multiple message protocols and can be deployed on distributed systems. It is lightweight and makes it easy to deploy applications. It mainly acts as a queue where a message which is entered can first be operated on. RabbitMQ runs on many operating systems and cloud environments and provides a wide range of developer tools for most popular languages. It is a Producer-Consumer style pattern where the producer sends a message and the consumer consumes it. The main features of RabbitMQ are mentioned below:
+ Asynchronous Messaging
+ Distributed Deployment
+ Management & Monitoring
+ Enterprise- and Cloud-Ready
###### Relative links:
+ https://dzone.com/articles/rabbitmq-in-microservices

## асинхронный vs синхронный вид коммуникации?
+ Synchronous protocol. HTTP is a synchronous protocol. The client sends a request and waits for a response from the service. That's independent of the client code execution that could be synchronous (thread is blocked) or asynchronous (thread isn't blocked, and the response will reach a callback eventually). The important point here is that the protocol (HTTP/HTTPS) is synchronous and the client code can only continue its task when it receives the HTTP server response.
+ Asynchronous protocol. Other protocols like AMQP (a protocol supported by many operating systems and cloud environments) use asynchronous messages. The client code or message sender usually doesn't wait for a response. It just sends the message as when sending a message to a RabbitMQ queue or any other message broker.
###### Relative links:
https://docs.microsoft.com/en-us/dotnet/architecture/microservices/architect-microservice-container-applications/communication-in-microservice-architecture

## возможные решениея для реализации аутентификации в микросервисной архитектуре?
1. Distributed Session Management
2. Client Token
3. Single sign-on
4. Client Token with API Gateway
5. Third-party application access
6. Mutual Authentication
###### Relative links:
+ https://medium.com/tech-tajawal/microservice-authentication-and-authorization-solutions-e0e5e74b248a
+ https://medium.com/@marcus.cavalcanti/stateless-authentication-for-microservices-9914c3529663
