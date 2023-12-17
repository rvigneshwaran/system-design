# System Design Basics

## Overview

This repository is a collection of resources and explanations covering various aspects of system design. Whether you're a beginner or an experienced developer, this repository aims to provide insights into fundamental system design concepts. The content is split by topics and examples are provided in each section.

## Part 1: Basics

1. [What is System Design?](#what-is-system-design)
2. [Horizontal vs. Vertical Scaling](#horizontal-vs-vertical-scaling)
3. [What is Capacity Estimation?](#what-is-capacity-estimation)
4. [What is HTTP?](#what-is-http)
5. [What is the Internet TCP/IP stack?](#what-is-the-internet-tcpip-stack)
6. [What happens when you enter Google.com?](#what-happens-when-you-enter-googlecom)
7. [What are Relational Databases?](#what-are-relational-databases)
8. [What are Database Indexes?](#what-are-database-indexes)
9. [What are NoSQL databases?](#what-are-nosql-databases)
10. [What is a Cache?](#what-is-a-cache)
11. [What is Thrashing?](#what-is-thrashing)
12. [What are Threads?](#what-are-threads)

## Part 2: Load Balancing

13. [What is Load Balancing?](#what-is-load-balancing)
14. [What is Consistent Hashing?](#what-is-consistent-hashing)
15. [What is Sharding?](#what-is-sharding)

## Part 3: DataStores

16. [What are Bloom Filters?](#what-are-bloom-filters)
17. [What is Data Replication?](#what-is-data-replication)
18. [How are NoSQL databases optimized?](#how-are-nosql-databases-optimized)
19. [What are Location-based Databases?](#what-are-location-based-databases)
20. [Database Migrations](#database-migrations)

## Part 4: Consistency vs. Availability

21. [What is Data Consistency?](#what-is-data-consistency)
22. [Data Consistency Levels](#data-consistency-levels)
23. [Transaction Isolation Levels](#transaction-isolation-levels)

## Part 5: Message Queues

24. [What is a Message Queue?](#what-is-a-message-queue)
25. [What is the publisher-subscriber model?](#what-is-the-publisher-subscriber-model)
26. [What are event-driven systems?](#what-are-event-driven-systems)
27. [Database as a Message Queue](#database-as-a-message-queue)

## Part 6: DevOps Concepts

28. [What is a Single Point of Failure?](#what-is-a-single-point-of-failure)
29. [What are Containers?](#what-are-containers)
30. [What is Service Discovery and Heartbeats?](#what-is-service-discovery-and-heartbeats)
31. [How to avoid Cascading Failures?](#how-to-avoid-cascading-failures)
32. [Anomaly Detection in Distributed Systems](#anomaly-detection-in-distributed-systems)
33. [Distributed Rate Limiting](#distributed-rate-limiting)

## Part 7: Caching

34. [What is Distributed Caching?](#what-is-distributed-caching)
35. [What are Content Delivery Networks?](#what-are-content-delivery-networks)
36. [Write Policies](#write-policies)
37. [Replacement Policies](#replacement-policies)

## Part 8: Microservices

38. [Microservices vs. Monoliths](#microservices-vs-monoliths)
39. [How monoliths are migrated](#how-monoliths-are-migrated)

## Part 9: API Gateways

40. [How are APIs designed?](#how-are-apis-designed)
41. [What are asynchronous APIs?](#what-are-asynchronous-apis)

## Part 10: Authentication Mechanisms

42. [OAuth](#oauth)
43. [Token Based Auth](#token-based-auth)
44. [Access Control Lists and Rule Engines](#access-control-lists-and-rule-engines)

## Part 11: System Design Tradeoffs

45. [Pull vs. Push](#pull-vs-push)
46. [Memory vs. Latency](#memory-vs-latency)
47. [Throughput vs. Latency](#throughput-vs-latency)
48. [Consistency vs. Availability](#consistency-vs-availability)
49. [Latency vs. Accuracy](#latency-vs-accuracy)
50. [SQL vs. NoSQL databases](#sql-vs-nosql-databases)

---

## What is System Design?

System design involves creating the architecture of a complex software system to meet specified requirements.

## Horizontal vs. Vertical Scaling

Horizontal scaling involves adding more machines, while vertical scaling involves increasing the resources of a single machine.

## What is Capacity Estimation?

Capacity estimation is the process of predicting the amount of load a system can handle.

## What is HTTP?

HTTP (Hypertext Transfer Protocol) is the foundation of data communication on the World Wide Web.

## What is the Internet TCP/IP stack?

The TCP/IP stack is the suite of communication protocols that enable network connectivity on the Internet.

## What happens when you enter Google.com?

Explains the steps and processes that occur when a user enters a website like Google.com.

## What are Relational Databases?

Relational databases organize data into tables and use SQL for querying and managing data.

## What are Database Indexes?

Database indexes improve the speed of data retrieval operations on a database.

## What are NoSQL databases?

NoSQL databases are non-relational databases designed for scalability, flexibility, and performance.

## What is a Cache?

A cache is a high-speed data storage layer that stores frequently accessed data.

## What is Thrashing?

Thrashing occurs when a computer's performance deteriorates due to excessive paging.

## What are Threads?

Threads are lightweight processes within a program that can run concurrently.

## What is Load Balancing?

Load balancing distributes incoming network traffic across multiple servers to ensure optimal resource utilization.

## What is Consistent Hashing?

Consistent hashing is a technique for distributing data across a network in a way that minimizes reorganization when nodes are added or removed.

## What is Sharding?

Sharding involves dividing a database into smaller, more manageable pieces called shards.

## What are Bloom Filters?

Bloom filters are space-efficient probabilistic data structures used to test whether an element is a member of a set.

## What is Data Replication?

Data replication involves copying data to multiple locations to improve reliability and fault tolerance.

## How are NoSQL databases optimized?

NoSQL databases are optimized for specific use cases, such as horizontal scaling and flexible data models.

## What are Location-based Databases?

Location-based databases store and retrieve data based on geographic locations.

## Database Migrations

Database migrations involve transferring data from one database to another while preserving data integrity.

## What is Data Consistency?

Data consistency ensures that data remains accurate and unchanged across the system.

## Data Consistency Levels

Describes different levels of data consistency, such as strong consistency and eventual consistency.

## Transaction Isolation Levels

Transaction isolation levels define the degree to which transactions are isolated from each other.

## What is a Message Queue?

A message queue is a communication method that allows applications to communicate asynchronously.

## What is the publisher-subscriber model?

The publisher-subscriber model involves communication between publishers and subscribers through a message broker.

## What are event-driven systems?

Event-driven systems respond to and handle events, triggering actions based on specific occurrences.

## Database as a Message Queue

Using a database as a message queue for communication between different components.

## What is a Single Point of Failure?

A single point of failure is a component that, if it fails, will cause the entire system to fail.

## What are Containers?

Containers encapsulate applications and their dependencies, providing a consistent and isolated environment.

## What is Service Discovery and Heartbeats?

Service discovery involves automatically finding and connecting to services, and heartbeats are signals indicating the health of a service.

## How to avoid Cascading Failures?

Strategies to prevent the spread of failures across a system.

## Anomaly Detection in Distributed Systems

Detecting abnormal behavior or performance in distributed systems.

## Distributed Rate Limiting

Implementing rate limiting across multiple components in a distributed system.

## What is Distributed Caching?

Distributed caching involves caching data across multiple nodes to improve performance.

## What are Content Delivery Networks?

Content Delivery Networks (CDNs) distribute content geographically for faster and more reliable delivery.

## Write Policies

Write policies determine how data is written to a cache.

## Replacement Policies

Replacement policies determine which items are removed from a cache when space is needed.

## Microservices vs. Monoliths

Comparison between microservices architecture and monolithic architecture.

## How monoliths are migrated

Strategies for migrating from monolithic to microservices architecture.

## How are APIs designed?

Design principles and considerations for creating effective APIs.

## What are asynchronous APIs?

Asynchronous APIs allow communication between components without waiting for an immediate response.

## OAuth

OAuth is an authorization framework for securing access to resources.

## Token Based Auth

Authentication using tokens for secure access to resources.

## Access Control Lists and Rule Engines

Access control lists and rule engines manage permissions and access in a system.

## System Design Tradeoffs

### Pull vs. Push

Choosing between pull (request-based) and push (notification-based) communication.

### Memory vs. Latency

Balancing the tradeoff between memory usage and system responsiveness.

### Throughput vs. Latency

Optimizing for either high throughput or low latency, depending on system requirements.

### Consistency vs. Availability

Navigating the tradeoff between data consistency and system availability.

### Latency vs. Accuracy

Balancing the tradeoff between response time and the accuracy of results.

### SQL vs. NoSQL databases

Comparing the characteristics and use cases of SQL and NoSQL databases.
