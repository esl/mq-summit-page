---
level: Introductory and overview
title: "When Software Starts Talking to Itself"
speakers:
- _participants/adi-polak.md

---
For decades, we’ve built messaging systems around a simple assumption: software receives an event, processes it, and produces a result. We’ve become remarkably good at making those systems reliable with ordering, retries, backpressure, state, replay, and failure recovery.

But what happens when the consumer is no longer a deterministic service?

AI agents can interpret events, make decisions, call tools, create new work, communicate with other agents, and change their behaviour based on what they observe. A single message can now trigger an unpredictable chain of actions across a distributed system.

This changes the meaning of some of our most fundamental guarantees.

In this keynote, we’ll explore how agentic systems are reshaping the distributed-systems problems we thought we had already solved, and why messaging infrastructure may become the critical coordination layer for autonomous software.

The future of messaging isn't just about moving data.
