# Event Driven Architecture : JMS et KAFKA (Page Event)

Event-Driven Architecture (EDA) relies on the fundamental principle of asynchronous communication between different components of a software system. Two key technologies that facilitate the implementation of EDA are Java Message Service (JMS) and Apache Kafka.

JMS, the Java standard for asynchronous messaging, provides a unified interface for Java applications to communicate by sending and receiving messages. It utilizes concepts such as queues and topics to orchestrate the transmission of messages. JMS promotes scalability and reliability, offering robust asynchronous communication within a distributed system.

On the other hand, Kafka, a distributed streaming platform, has emerged as an essential solution for EDA. Designed to handle massive volumes of real-time data, Kafka uses a publish/subscribe model based on topics. It offers exceptional scalability, low latency, and high data durability. Kafka is particularly well-suited for modern architectures requiring continuous event processing and has become a cornerstone for building real-time data pipelines.

### Spring Cloud Stream Kafka - PageEvent Entity
![PageEvent](https://github.com/Ennia-Fahd/TP6--Kafka_EeventDriver_Architecture/assets/92646945/1f962b0a-3fc0-405e-b1c1-de79c86d85ba)

The PageEvent entity is employed in the broader context of a Spring Cloud Stream and Kafka setup, where it serves as a structured representation of events related to page interactions. The entity's fields capture essential information about each event, facilitating the seamless exchange and processing of real-time data within the application.
### Topic R2 (Page Event Supplier):
![R2](https://github.com/Ennia-Fahd/TP6--Kafka_EeventDriver_Architecture/assets/92646945/9143d359-13dd-4b8e-ba04-26052f1e305c)
### Topic R3 (Page Event Function):
![R3](https://github.com/Ennia-Fahd/TP6--Kafka_EeventDriver_Architecture/assets/92646945/cf5f6aa0-6d10-470a-947e-6d4b678786c0)
### Analysis operations (Count the number of pages filtered according to their durations) :
![kafkaAnalytics](https://github.com/Ennia-Fahd/TP6--Kafka_EeventDriver_Architecture/assets/92646945/bbf35986-f1e8-4fa2-a6aa-103050ebc360)
### Smoothie JS :
![KafkaFin](https://github.com/Ennia-Fahd/TP6--Kafka_EeventDriver_Architecture/assets/92646945/afc921b0-9f0c-406d-b927-6a760305ba95)

Smoothie.js is a lightweight and efficient JavaScript library designed to simplify the implementation of real-time, live-updating user interfaces. While not inherently tied to Event-Driven Architecture (EDA) or Apache Kafka, Smoothie.js can be a valuable tool in visualizing and presenting data streams, which aligns well with the principles of EDA and Kafka's capabilities.

In the context of EDA, where events play a central role in system communication, Smoothie.js can be utilized to create dynamic and interactive dashboards that display real-time event data. By seamlessly updating charts and graphs as new events are received, Smoothie.js enhances the user experience by providing instant visibility into the evolving state of the system.

When integrated with Kafka, Smoothie.js can be employed to visualize Kafka-produced and consumed events. Kafka's publish/subscribe model aligns with the real-time data processing requirements, and Smoothie.js complements this by offering smooth and responsive data visualizations. For instance, a Smoothie.js-powered live chart could represent the throughput of Kafka topics, allowing users to monitor message rates and patterns.
