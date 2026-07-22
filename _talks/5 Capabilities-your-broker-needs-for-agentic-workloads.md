---
tags:
  - AI
  - Operating, optimizing and scaling
level: Intermediate
title: "5 Capabilities Your Broker Needs for Agentic Workloads"
speakers:
- _participants/stefan-moser.md
- _participants/vignesh-selvam.md

---
Every agent framework is quietly reimplementing broker capabilities from scratch. Routing? Reimplemented per-framework. Retries? Each one rolls its own. Discovery, fan-out, backpressure, dead-lettering, durable execution: all reinvented in application code, inside a single process, with predictable results. Message brokers have solved these problems for decades, but today's brokers weren't designed for consumers that are stateless, non-deterministic, and expensive to invoke. Both sides need to evolve. This talk identifies the five properties a message broker must take on to serve agentic workloads natively, so agent frameworks can stop pretending to be infrastructure and get back to being applications.

**Key Takeaways:**
* Attendees will learn to recognize where agent orchestration frameworks are reimplementing messaging infrastructure,
* understand the specific demands that agentic workloads place on brokers that today's designs do not address,
* and leave with a clear picture of the capabilities their broker must gain to support this new class of consumer.

**Target Audience:**
* Messaging engineers, architects, and technical leaders who operate message brokers in production and are starting to see agent-driven workloads arrive on their infrastructure. No prior AI or agent framework experience required.
