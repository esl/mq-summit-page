---
tags:
  - cloud, edge, IoT, AI
  - Operating, optimizing and scaling
level: Intermediate
title: "5 Capabilities Your Broker Needs for Agentic Workloads"
speakers:
- _participants/stefan-moser.md
- _participants/vignesh-selvam.md

---
Most messaging systems look reliable until the network stops behaving like a network.
In autonomous maritime environments, connectivity becomes intermittent, bandwidth-constrained, high-latency, and sometimes unavailable entirely. Telemetry arrives from drones, vessels, sensors, CAN bus, AIS, LTE, SATCOM, and edge systems , each with different protocols, schemas, delivery guarantees, and operational constraints.

This talk shares lessons from MAPS Messaging’s NATO DIANA 2026 work validating resilient messaging architectures for autonomous maritime systems operating across degraded networks.

The session examines trade-offs that determine whether distributed systems remain operational under failure conditions: protocol mediation versus broker bridging, buffering versus dropping, filtering versus forwarding, and replay recovery versus replay storms.

Attendees will leave with practical patterns for designing messaging systems that degrade gracefully instead of failing catastrophically.

**Key Takeaways:**
* Why “message delivered” becomes an incomplete guarantee under degraded, intermittent, or bandwidth-constrained connectivity.
* How protocol mediation differs from broker bridging and point-to-point integration — and where each approach breaks down.
* The operational trade-offs between transforming, filtering, down-sampling, buffering, and forwarding telemetry.
* How to design replay and recovery mechanisms without overwhelming downstream systems after reconnection.
* Why the failure modes exposed by autonomous maritime systems increasingly apply to cloud, edge, IoT, industrial, and AI-driven distributed architectures.
* Practical patterns for building messaging systems that degrade gracefully instead of failing catastrophically.

**Target Audience:**
* Architects, senior engineers, SREs, DevOps engineers, platform teams, messaging practitioners, and IoT/edge system designers building or operating distributed systems in production. Also relevant for technical leaders responsible for interoperability, resilience, and long-term messaging architecture decisions.
* The talk is especially applicable to teams working with event-driven systems, heterogeneous protocols, edge deployments, intermittent connectivity, or mission-critical messaging environments.
