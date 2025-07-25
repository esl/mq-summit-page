---
level: Introductory and overview
title: "You Keep Using That Word"
speakers:
- _participants/sam-newman.md

---
When it comes to distributed computing, one of the perennial topics comes down to how different services should communicate. Working out the relative merits of specific technical approaches can become a complex affair however, so we often reach for categorisation to simplify our work. Often, the discussion around inter-process communication hinges on what on the face of it seems to be a simple decision: Synchronous or Asynchronous. Just saying “we’re cloud native!” isn’t enough if you actually want to get anywhere, unless your goal is simply to dump loads of money into the hands of tech vendors and consultants.

Unfortunately, it turns out that this is far from a simple assessment of what approach is best. Aside from many nuances around this topic, the main issue is that it seems that people can’t even agree on what asynchronous means! Is it non-blocking clients? Message-broker based communication? Does only inbox-based message passing apply?

In this talk, we’ll explore the meaning of asynchronous in the context of distributed systems, and show that using the same word in ever-so slightly different contexts causes a huge amount of confusion.
