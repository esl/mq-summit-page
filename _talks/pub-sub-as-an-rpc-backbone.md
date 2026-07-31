---
tags:
  - NATS
level: Intermediate
title: "Pub/Sub as an RPC Backbone: Rebuilding gRPC's Patterns on NATS with CloudEvents and Tower"
speakers:
- _participants/christopher-coco.md

---
gRPC dominates how we think about RPC, but its tight coupling to HTTP/2 can be awkward when your architecture is built on a message broker. At Verrus we replaced gRPC with a transport-agnostic RPC framework that runs natively over NATS, using CloudEvents (https://cloudevents.io/) as the on-the-wire envelope and Protobuf as the source of truth.

The result is unary, fire-and-forget, and server-streaming calls over pub/sub with queue-group load balancing, deadline propagation, cooperative cancellation, and OpenTelemetry trace context flowing end-to-end. The implementation is in Rust on top of async-nats, prost, and tower, but the design decisions are language-agnostic and the patterns translate to any broker-backed RPC layer.

This talk walks through the call lifecycle, the NATS-specific patterns that made it work, and the messaging tradeoffs we hit along the way -- including where pub/sub-as-RPC genuinely wins over gRPC and where it costs you.

**Key Takeaways:**
* By the end of the session, I'm hopeful that attendees will be able to:
* Recognize when a broker-backed RPC layer is a better fit than gRPC, and articulate the specific tradeoffs involved.
* Design a structured NATS subject scheme that supports queue-group load balancing alongside tenant and deployment-variant isolation.
* Implement server-side streaming on top of a request/reply broker using reply-inbox subjects and an end-of-stream sentinel.
* Propagate deadlines, distributed tracing context, and cancellation signals through a message broker without losing observability.
* Apply these patterns to other brokers (Kafka, RabbitMQ, AMQP) where the same transport-agnostic design holds.

**Target Audience:**
* Backend engineers and architects building service-to-service communication on a message broker. Particularly relevant for teams who have hit gRPC's limits in broker-centric architectures, teams designing greenfield event-driven platforms, and anyone who has wondered why their RPC framework and their messaging layer feel like two separate worlds.
* Familiarity with NATS basics (publish, subscribe, request/reply, queue groups) and the gRPC mental model (services, methods, status codes) is expected. No Rust knowledge required -- the design decisions are language-agnostic and code samples are kept high-level.
