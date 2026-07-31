---
tags:
  - IBM MQ
level: Intermediate
title: "Resilient Messaging... How Hard Can It Be?"
speakers:
- _participants/jon-rumsey.md

---
Transactions, persistence and availability are all fairly easy to manage when there is only one server. However, the bar is much higher for messaging solutions - they’re expected to just be there and trusted to transport valuable data. What happens when a disk fails? the network fails? a node fails? or worse case - your entire data centre fails?

**Key Takeaways:**
* The audience will be able to learn how MQ achieves the basics like message persistence and transactionality using a recovery log. The talk will then cover what happens when components fail, how can MQ provide redundancy, look at the difference between message and service availability and how IBM implemented raft based distributed consensus.

**Target Audience:**
* All messaging enthusiasts! Architects, developers and ops roles who have a curiosity in how message queuing works.
