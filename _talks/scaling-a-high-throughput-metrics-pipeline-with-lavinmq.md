---
tags:
  - AMQP, LavinMQ
level: Intermediate
title: "Scaling a High-Throughput Metrics Pipeline with LavinMQ"
speakers:
- _participants/magnus-landerblom.md

---
As systems scale, the telemetry and metrics pipelines that monitor them face immense pressure. This talk presents the architectural evolution of the CloudAMQP metrics pipeline, which grew from processing data from 3,000 to over 15,000 servers. This five-fold increase in producers required a fundamental rethinking of our data ingestion and processing architecture to handle throughputs exceeding 18,000 messages per second without compromising data integrity or system resilience.

At the core of our solution is LavinMQ. We will deep-dive into the specific AMQP patterns we leveraged to solve two critical distributed computing problems: maintaining data ordering during horizontal scaling and managing backpressure from slow or unavailable downstream consumers.

**Talk objectives:**
- There are a lot of users of both RabbitMQ and LavinMQ that uses these brokers on a daily bases but are still missing some really valuable features that are built into the broker. This talk will highlight some of them and give example for how they can be used.

**Target Audience:**
- People that are used to working with message queuing that are unsure how to scale up or use a message queuing broker but have a feeling that they don't utilize the full potential in the broker.
