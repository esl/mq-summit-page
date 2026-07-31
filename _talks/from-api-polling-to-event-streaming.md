---
tags:
  - Apache Kafka
  - Community Highlights
level: Intermediate
title: "From API Polling to Event Streaming: Lessons Learned at PostNL"
speakers:
- _participants/jeroen-van-disseldorp.md
- _participants/guy-hagemans.md

---
As parcel volumes grow, continuously polling APIs for status updates becomes increasingly inefficient. At PostNL, this challenge led to the adoption of an event-driven approach where parcel status changes are published and consumed in real time. This session shares the practical lessons learned while introducing event streaming into a large logistics organisation. We discuss how to determine when APIs, events, or file-based integrations are the right choice, how data ownership and governance can be organised across teams, and why schema management is critical for maintaining data quality at scale. We also cover event design, stream processing, observability, and security, highlighting the operational challenges we encountered and the lessons learned while driving adoption across the organisation. The focus is on the architectural and organisational trade-offs involved in building and operating a production event-streaming platform.

**Key Takeaways:**
* Share real-world lessons from a project that moved a specific solution for parcel notifications from an API-driven approach to an event-driven approach based on Kafka.

**Target Audience:**
* Software/solution Architects, Developers, Integration specialists, project managers
