---
tags:
  - Apache Kafka, RabbitMQ, Amazon MQ, Apache ActiveMQ
  - Operating, optimizing and scaling
level: Intermediate
title: "Queues vs. Logs: Choosing the Right Backbone for Event-Driven Architectures"
speakers:
- _participants/ali-alemi.md
- _participants/vinodh-kannan-sadayamuthu.md

---
Not every event-driven system needs Kafka, and not every message needs a queue. In this session, we break down the architectural decision between MQ message brokers and event streaming platforms (Apache Kafka). You'll learn when point-to-point routing, dead-letter queues, and transactional messaging make queues the right choice — and when append-only logs, consumer groups, and replay capabilities demand a streaming platform. We'll walk through real-world patterns including command vs. event separation, hybrid topologies, and migration paths from legacy brokers to streaming. You'll leave with a decision framework to match your workload characteristics — ordering, throughput, retention, and coupling — to the right technology.

**Key Takeaways:**
* By the end of this session, attendees will be able to differentiate between message queues and event streaming platforms based on workload characteristics — not hype. They'll understand when to use point-to-point messaging with routing, filtering, and dead-letter handling versus append-only logs with replay, ordering guarantees, and parallel consumption. Attendees will walk away with a decision framework mapping requirements like throughput, retention, coupling, and delivery semantics to the right technology choice. They'll also recognize common anti-patterns that lead to operational debt and learn how to avoid them before they become costly production problems.

**Target Audience:**
* Software architects, backend developers, and platform engineers designing or evolving event-driven systems. This session is ideal for teams currently evaluating messaging technologies, those experiencing operational challenges with their existing choice, or anyone building distributed systems who wants to make informed infrastructure decisions. No prior expertise in Kafka or RabbitMQ is required — just a working understanding of distributed systems fundamentals.
