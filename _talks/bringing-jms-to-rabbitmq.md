---
tags:
  - RabbitMQ, JMS, AMQP, Apache ActiveMQ, Azure Service Bus
  - Use-cases (messaging and streaming in action)
level: Advanced
title: "Bringing JMS to RabbitMQ: AMQP 1.0 and Cross-Broker Interoperability"
speakers:
- _participants/David-Ansari.md

---
Java Message Service (JMS) remains a widespread and popular standard in many enterprises. A key promise of JMS is interoperability: applications should not need code changes when switching the backend message broker. In this talk, we explore how RabbitMQ fulfills this promise using the AMQP 1.0 protocol and the AMQP JMS Mapping specification.

We will demonstrate how the Apache Qpid JMS client can seamlessly talk to multiple AMQP 1.0 brokers - including RabbitMQ, Azure Service Bus, and ActiveMQ - proving that modern JMS brokers do not need to be written in Java. Finally, we will showcase the new JMS queue type introduced in VMware Tanzu RabbitMQ, which brings broker-side message selectors and queue browsing using Raft-based data safety to the JMS ecosystem.

**Key Takeaways:**
* Highlight JMS Interoperability: Show how the AMQP JMS Mapping specification (an AMQP 1.0 extension) enables a single JMS client to connect to diverse brokers without code changes.
* Break the Java-Broker Myth: Demonstrate that modern, robust JMS brokers do not have to be written in Java, using RabbitMQ (Erlang) and Azure Service Bus as examples.
* Introduce VMware Tanzu RabbitMQ JMS Features: Transparently showcase the new commercial JMS queue type, detailing how it supports broker-side message selectors, queue browsers, and delivery delays while leveraging Raft for data safety.

**Target Audience:**
* Java Developers and Enterprise Architects who maintain or build JMS applications and want to modernize their messaging infrastructure without rewriting code.
* Technical Decision Makers looking to consolidate their messaging middleware onto a single, robust platform while still supporting legacy JMS workloads.
* Message Broker Administrators interested in how AMQP 1.0 enables cross-broker compatibility and interoperability.
