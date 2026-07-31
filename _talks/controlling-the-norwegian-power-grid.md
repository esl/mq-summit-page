---
tags:
  - Apache Kafka
  - Community Highlights
level: Introductory and overview
title: "Controlling the Norwegian Power Grid in Real Time with Apache Kafka"
speakers:
- _participants/herman-jakobsen.md

---
In March 2025, the Norwegian Transmission System Operator, Statnett, implemented its biggest operational and digital change in 30 years! By shifting from manual, 60-minute balancing to automated activation with 15-minute intervals, the digital transformation ensures a more efficient, resilient, and stable electricity grid. And the backbone of it all: Apache Kafka!

We will take both an architectural and client-side dive into how Apache Kafka is used in the control loop of the Norwegian power grid, and explore how Kafka is used not only as an integration between systems, but also as a platform for streaming and aggregating data in real-time. All of this while still meeting strict requirements for robustness, observability, availability and fault-tolerance.

**Key Takeaways:**
* Knowledge of how the power grid is controlled
* How Kafka can be used to integrate systems, and stream and aggregate data in real-time
* How to design robust value chains that meets consumers’ different requirements of real-time data vs historical correct data (i.e. handle delayed data, backfilling etc)
* How to monitor and gain observability in a complex and long value chain
* If time, how to design efficient, simple and robust Kafka Streams clients (frankly, I think this will be skipped).

**Target Audience:**
* Everyone interested in how Apache Kafka is used in real high-stake use cases. Developers interested in how to design robust value chains and Kafka Streams clients.
