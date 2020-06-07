---
tags: [Distributed Systems]
title: Eventual Consistency
created: '2020-06-07T13:28:57.697Z'
modified: '2020-06-07T13:31:13.294Z'
---

# Eventual Consistency

Eventual consistency is a consistency model used in distributed computing to achieve high availability that informally guarantees that, if no new updates are made to a given data item, eventually all accesses to that item will return the last updated value.

Eventually-consistent services are often classified as providing BASE (Basically Available, Soft state, Eventual consistency) semantics, in contrast to traditional ACID (Atomicity, Consistency, Isolation, Durability) guarantees.

- **B**asically **A**vailable: basic reading and writing operations are available as much as possible (using all nodes of a database cluster), but without any kind of consistency guarantees (the write may not persist after conflicts are reconciled, the read may not get the latest write)
- **S**oft state: without consistency guarantees, after some amount of time, we only have some probability of knowing the state, since it may not yet have converged
- **E**ventually consistent: If the system is functioning and we wait long enough after any given set of inputs, we will eventually be able to know what the state of the database is, and so any further reads will be consistent with our expectations

See also: [](./ACID.md)
