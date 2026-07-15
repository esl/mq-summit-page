---
tags:
  - RabbitMQ
  - Operating, optimizing and scaling
level: Advanced
title: "Bringing infinite streaming to RabbitMQ"
speakers: -_participants/michael-davis.md

---
At MQ Summit 2025, we (Amazon MQ) talked about our plans to make storage for RabbitMQ streams practically bottomless. Since then we've created an open-source RabbitMQ plugin "rabbitmq-stream-s3" which bridges streams and S3 storage. This talk will explain the plugin's motivation and concepts, and then we will take a look back at how the design has evolved and examine the challenges and pitfalls we've faced.

**Key Takeaways:**
- The audience will walk away knowing:
* The basics of streaming and how it's different than messaging.
* An overview of how streaming works in RabbitMQ.
* Storage challenges of "vanilla" streaming in RabbitMQ and the motivations behind our plugin "rabbitmq-stream-s3".
* How "rabbitmq-stream-s3" works under the hood and how it compares to other tiered-storage implementations like Kafka KIP-405.

**Target Audience:**
* Platform Engineers & Infrastructure Architects - Teams responsible for designing and scaling streaming infrastructure
* RabbitMQ Operators & Site Reliability Engineers - Professionals managing RabbitMQ deployments facing cost pressures from disk resource footprints
* Backend Engineers & System Designers - Developers building high-throughput streaming applications who need to understand resource footprint implications
