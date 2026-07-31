---
tags:
  - Apache Kafka, Redpanda, AI
  - Community Highlights
level: Introductory and overview
title: "From Queues to Logs and Back Again"
speakers:
- _participants/viktor-gamov.md

---
Welcome to a brief history of messaging, told as a story of constraints falling away. I will start in the era of the queue, when a broker's job was to move a message and forget it. Around 2011, Kafka inverted the model: keep messages, make the log durable, and let consumers replay history instead of reading it once. That one idea reshaped our architectures (stream processing, event sourcing) and turned a messaging system into the place where companies keep their source of truth. Fast forward to now: ZooKeeper is gone, storage is moving to object stores, and queues are returning to Kafka via shared groups. And we look forward. We made data durable and replayable. It's time to hand that substrate to AI agents that need memory, context, and a record of what just happened. I'll make the case that the messaging layer is where agentic systems will live. Whether you run anything with "MQ" in the name, you'll leave with a map of how we got here and a strong opinion about where we're headed.

**Key Takeaways:**
* Attendees will leave with a mental model of how messaging moved from transient queues to the durable log, what Kafka actually changed and the architectures it enabled, and where the field stands today after ZooKeeper, with object-storage brokers (like warpstream) and share groups bringing queues back. They'll be able to reason about messaging tradeoffs across RabbitMQ, Kafka, NATS, and Pulsar by capability rather than allegiance, and they'll leave with a clear point of view on why the event log becomes the substrate for the next wave of AI agents.

**Target Audience:**
* Whether you run RabbitMQ, Kafka, NATS, or something else with "MQ" in the name, you'll leave with a map of how we got here and a strong opinion about where we're headed.
