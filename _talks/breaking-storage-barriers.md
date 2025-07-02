---
tags:
  - RabbitMQ
level: Intermediate
title: "Breaking Storage Barriers: How RabbitMQ Streams Scale Beyond Local Disk"
speakers:
- _participants/simon-unge.md

---
As streaming workloads grow, storage becomes the bottleneck that limits RabbitMQ deployments. This technical deep-dive explores how to break through local disk barriers using tiered storage architecture. You'll learn the fundamentals of RabbitMQ stream storage - from segment files to I/O operations - and discover how to seamlessly extend existing systems through file abstraction layers. We'll cover implementing storage backends that preserve write performance while enabling transparent reads across tiers, all without disrupting live streaming workloads.

**Talk objectives:**
* Understand RabbitMQ Streams storage fundamentals - Deep dive into how RabbitMQ manages segment files, indexes, and I/O operations today, providing the foundation for understanding why tiered storage can be added seamlessly
* Master non-disruptive architecture evolution - Learn how to extend existing systems by working at the file abstraction layer rather than rewriting core streaming logic, demonstrating a surgical approach to adding major features without breaking existing functionality
* Implement low-level storage abstractions - Explore how changing just the file I/O interface allows transparent integration with multiple storage backends while preserving all existing write paths, read semantics, and replication mechanisms
* Maintain stream performance at scale - Learn strategies for preserving write performance while enabling transparent reads across storage tiers, including manifest-based metadata management and drive abstraction patterns that work within existing RabbitMQ architecture

By the end of this talk, attendees will have a clear roadmap for implementing cost-effective, scalable stream storage solutions that grow with their business needs while maintaining the reliability and performance RabbitMQ users expect - all without disrupting existing streaming workloads.

**Target Audience:**

Primary Audience:
* Platform Engineers & Infrastructure Architects - Teams responsible for designing and scaling messaging infrastructure who need to solve storage capacity and cost challenges
* RabbitMQ Operators & Site Reliability Engineers - Professionals managing RabbitMQ deployments facing storage limitations, retention requirements, or cost pressures from growing stream data
* Backend Engineers & System Designers - Developers building high-throughput streaming applications who need to understand storage implications

Secondary Audience:
* Technical Decision Makers & Engineering Managers - Leaders evaluating messaging infrastructure investments and needing to understand cost-effective scaling strategies
* DevOps Engineers - Teams responsible for deploying and maintaining streaming infrastructure in cloud and hybrid environments
* Data Engineers - Professionals working with event streaming and data pipelines who need reliable, scalable storage for stream processing workloads
