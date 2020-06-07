---
tags: [Distributed Systems]
title: CAP - Theorem
created: '2020-06-01T10:38:04.512Z'
modified: '2020-06-07T13:24:49.906Z'
---

# CAP - Theorem

In theoretical computer science, the CAP theorem states that it is impossible for a distributed data store to simultaneously provide more than two out of the following three guarantees:

- **Consistency:** Every read receives the most recent write or an error
- **Availability:** Every request receives a (non-error) response, without the guarantee that it contains the most recent write
- **Partition tolerance:** The system continues to operate despite an arbitrary number of messages being dropped (or delayed) by the network between nodes
