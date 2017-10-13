---
layout:    presentation
title:     "A comprehensive study of Convergent and Commutative Replicated Data Types"
presenter: Alex Weber
date:      2017-10-25
time:      7:30pm - 8:30pm
location:  skullspace
upcoming:  true
---

This presentation will discuss a simple, theoretically sound approach to eventual consistency. The concept of a convergent or commutative replicated data type (CRDT) will be introduced, for which some simple mathematical properties ensure eventual consistency. A trivial example of a CRDT is a replicated counter, which converges because the increment and decrement operations commute (assuming no overflow). Provably, replicas of any CRDT converge to a common state that is equivalent to some correct sequential execution. As a CRDT requires no synchronisation, an update executes immediately, unaffected by network latency, faults, or disconnection. It is extremely scalable and is fault-tolerant, and does not require much mechanism. CRDTs are used by chat system, collaborative editing systems, and NoSQL databases.

[Alex Weber](https://twitter.com/alexwebr) is a Director of BSides Winnipeg, and a co-host of Papers We Love Winnipeg. His day job at Tenable Network Security involves working on the Nessus vulnerability scanner. Alex has a hobbyist interest in cryptography, compilers, and application security.
