---
tags:
  - Amazon SQS
level: Intermediate
title: "Multi-Tenant messaging systems"
speakers:
- _participants/dirk-froehner.md
- _participants/artem-gayardo-matrosov.md

---
This talk explores the architectural challenges and solutions for building scalable multi-tenant messaging systems. We'll examine isolation strategies, including shared versus dedicated queue architectures and their trade-offs. We will cover authentication and authorization frameworks to prevent cross-tenant data access and tackle the "noisy neighbor" problem—where high-volume tenants might impact others' performance.

**Talk objectives:**
- Evaluate isolation architectures
- Compare shared queue versus dedicated queue models, understanding when to apply each approach based on tenant requirements, cost constraints, and performance targets and mitigate noisy neighbor effects.

**Target Audience:**
- Developers & Architects
