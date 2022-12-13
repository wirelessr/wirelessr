# Software Architect Experience Notes

Hi folks.

I'm a software architect, and every Monday I post a regular piece on [Medium](https://medium.com/@lazypro) about my work and studies. Here I will try to organize those contents into a publication by category.

If you want to see the latest content, feel free to subscribe to my [Medium](https://medium.com/@lazypro).

## MySQL, Postgres

- [How to avoid the race condition and the negative value](https://medium.com/interviewnoodle/how-to-avoid-the-race-condition-and-the-negative-value-3f397b2b08e4)
- [Solve Phantom Read in MySQL](https://betterprogramming.pub/solve-phantom-read-in-mysql-a1c85f9a8c56)
- [Understanding Partial Indexing](https://betterprogramming.pub/partial-indexing-faq-55d6f1e10c08)
- [Understanding String Comparison of Databases](https://betterprogramming.pub/understanding-string-comparison-of-databases-9bde87f2006d)

## MongoDB
- [How to choose a MongoDB shard key](https://medium.com/interviewnoodle/how-to-choose-a-mongodb-shard-key-e4063b636c26)
- [Data Persistence in MongoDB](https://towardsdev.com/data-persistence-in-mongodb-1ca91f88914)
- [Read-after-write Consistency in MongoDB](https://towardsdev.com/read-after-write-consistency-in-mongodb-ea4cd91d0d3)
- [Array Operation in MongoDB](https://towardsdev.com/array-operation-in-mongodb-2c6f6eb2114b)
- [The Mystery of MongoDB Indexing](https://betterprogramming.pub/the-mystery-of-mongodb-indexing-af61766647dc)
- [Archiving MongoDB Changes to AWS S3](https://lazypro.medium.com/archiving-mongodb-changes-to-aws-s3-9537f793d5a8)

## Redis
- [Redis helps avoiding racing conditions](https://lazypro.medium.com/redis-helps-avoiding-racing-conditions-b970ba3fdd58)
- [Data Persistence in Redis](https://towardsdev.com/data-persistence-in-redis-2780c11d1623)
- [Cardinality Counting in Redis](https://towardsdev.com/cardinality-counting-in-redis-3c3a472e2d9f)
- [Redis as a Lock! Are You Sure?](https://betterprogramming.pub/redis-as-a-lock-are-you-sure-a870c9f22ad8)
- [Explain Redlock in Depth](https://lazypro.medium.com/explain-redlock-in-depth-dba95c107102)


## Software Testing
- [What’s Difference Between Unit Test and Integration Test](https://medium.com/interviewnoodle/whats-difference-between-unit-test-and-integration-test-aae6ef13220)
- [Property-Based Testing Framework for Node](https://betterprogramming.pub/property-based-testing-framework-for-node-1ca702ad30bc)
- [Gitlab CI for Node Testing and Coverage](https://lazypro.medium.com/gitlab-ci-for-node-testing-and-coverage-d8f8c82f8c1e)
- [How to Determine API Slow Downs](https://medium.com/better-programming/how-to-know-api-is-slowing-down-2957b9e1341d)

## Architecture Pattern
- CQRS
    - [Shift from Monolith to CQRS](https://medium.com/interviewnoodle/shift-from-monolith-to-cqrs-a34bab75617e)
    - [Solve Performance Bottleneck through CQRS](https://lazypro.medium.com/solve-performance-bottleneck-through-cqrs-3fd456df1551)
    - [Reducing Database Loading](https://betterprogramming.pub/reducing-database-loading-b54f2d8edb39)
- Distributed Transaction
    - [Distributed Transaction Introduction](https://medium.com/interviewnoodle/distributed-transaction-introduction-1cd105c830a2)
    - [Design Distributed Transaction With Practical Examples](https://betterprogramming.pub/design-distributed-transaction-with-practical-examples-7b1d93fddb63)
- Event-driven Architecture
    - [Design Patterns of Event-driven Architecture, Part 1](https://lazypro.medium.com/design-patterns-of-event-driven-architecture-bf0121cfda7b)
    - [Design Patterns of Event-driven Architecture, Part 2](https://lazypro.medium.com/design-patterns-of-event-driven-architecture-part-2-ea4296dc58d)
    - [Kafka vs. RabbitMQ](https://medium.com/interviewnoodle/kafka-vs-rabbitmq-bc9c8dc7768a)
    - [Message Queue in Redis](https://selectfrom.dev/message-queue-in-redis-9efe0de2c39c)
    - [Message Queue in Redis, Part 2](https://lazypro.medium.com/message-queue-in-redis-part-2-61c0d22735fe)
    - [Understand Temporal Coupling in Code](https://betterprogramming.pub/temporal-coupling-in-code-e74899f7a48f)
    - [Implement Event-driven Architecture With Minimal Effort](https://betterprogramming.pub/implement-event-driven-architecture-with-minimal-effort-182c3bbe5524)
    - [Streaming Architecture Introduction](https://lazypro.medium.com/stream-processing-introduction-796f15061880)
    - [Design Pattern of Streaming Enrichment](https://betterprogramming.pub/design-pattern-of-streaming-enrichment-17a9eb065eca)
    - [Understanding Exactly-once Semantics](https://medium.com/@lazypro/understanding-exactly-once-semantics-338a56d8ba6a)
- Resilient Engineering
    - [Resilient Caching in Redis](https://towardsdev.com/resilient-caching-in-redis-a5b3c1a49f14)
- Design Principle
    - [Layered Architecture Clarification](https://lazypro.medium.com/layered-architecture-clarification-e55b69d60e98)
    - [Are Design Pattern and Clean Code Useful?](https://lazypro.medium.com/are-design-pattern-and-clean-code-useful-cb1861846a58)
    - [How to Design Software in a Clean Architecture Way](https://betterprogramming.pub/how-to-design-in-clean-architecture-way-part-1-36c3e558517b)
    - [Designing Software Using Clean Architecture: Domain-Driven Design](https://betterprogramming.pub/how-to-design-in-clean-architecture-way-part-2-8524e76f2720)
    - [Combine Domain-Driven Design and Databases](https://lazypro.medium.com/combine-domain-driven-design-and-databases-747fa36ec642)
- Non-functional Requirements, e.g., Scalibility, Consistency
    - [Scaling Web Service](https://betterprogramming.pub/scaling-web-service-b391557a1134)
    - [Consistency between Cache and Database, Part 1](https://lazypro.medium.com/consistency-between-cache-and-database-part-1-f64f4a76720)
    - [Consistency between Cache and Database, Part 2](https://lazypro.medium.com/consistency-between-cache-and-database-part-2-e28fc7f8a7c3)
    - [Scalability vs. Elasticity](https://betterprogramming.pub/scalability-vs-elasticity-cfae2d7a19b)
    - [Solving Dogpile Effect](https://medium.com/@lazypro/solving-dogpile-effect-9d869174d302)
- Data Infra
    - [Evolutionary Data Infrastructure](https://betterprogramming.pub/evolutionary-data-infrastructure-4ddce2ec8a7e)
    - [Evolutionary from Batching to Streaming](https://blog.devgenius.io/evolutionary-from-batching-to-streaming-7a9a7942922)
    - [The Infrastructure Stack for Real-Time Data Analysis](https://medium.com/better-programming/real-time-data-infra-stack-73c597ed05ee)

## Microservice
- [Do you really need a microservice?](https://medium.com/interviewnoodle/do-you-really-need-a-microservice-91a48cbea8c1)
- [Original Sin of Microservices, Part 1](https://medium.com/interviewnoodle/original-sin-of-microservices-part-1-90461ddcefb)
- [Original Sin of Microservices, Part 2](https://lazypro.medium.com/original-sin-of-microservices-part-2-8856c0e8426d)
- [Design an E-commerce Website From a High-level Perspective](https://betterprogramming.pub/design-an-e-commerce-website-from-a-high-level-perspective-184618741ee8)

## Workflow

- [Trunk-based Development Can Help](https://lazypro.medium.com/trunk-based-development-can-help-4bb425595c00)
- [How Kanban Works and Why I Prefer It Over Scrum](https://betterprogramming.pub/improve-the-productivity-by-using-agile-development-778c7f069c6a)
- [How to Prepare a Design Review Like an Expert?](https://betterprogramming.pub/how-to-prepare-a-design-review-like-an-expert-85d2ab85d7f5)
- [Introduction to Feature Toggling— Types, Use Cases and Implementation](https://betterprogramming.pub/feature-toggle-introduction-68d58f5c709)
- [Unleash vs. LaunchDarkly: A Look at Feature Toggling Solutions](https://betterprogramming.pub/unleash-vs-launchdarkly-c35f586ccf49)
