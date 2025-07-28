---
tags:
  - Celery
  - Redis Streams
level: Intermediate
title: "An Introduction to Messaging in Valkey"
speakers:
- _participants/roberto-luna-rojas.md

---
You’ve probably used Valkey (or its predecessor) as a cache, however, hiding below the surface is a messaging powerhouse built for both scale, low latency, and high throughput. In this session, you’ll learn about Valkey, a Linux Foundation back, high-speed, Key-Value datastore, provides both fundamental primitives and complete solutions for a variety of messaging use cases.

**Talk objectives:**
Attendees will learn about:
* Valkey, it’s history as a fork of Redis OSS, and where it’s evolving
* Why and how of in-memory messaging
* What capabilities baked capabilities in for messaging (each with examples)
  * Fire and forget pubsub
  * Lists as Queues
  * Sorted Sets as priority queues
  * Kafka-like streams
* The projects which can use Valkey as a backing storage engine, including:
  * BullMQ
  * Celery
  * Sidekiq
  * KEDA
* What performance they can expect out of Valkey
* How to get involved with Valkey"

**Target Audience:**
- This session targets folks interested performance in messaging as well as those looking to build lighter weight systems.
