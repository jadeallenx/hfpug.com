---
title: "January 2020"
date: 2020-01-09T20:59:17-06:00
draft: false
---
This month Gyan Aggarwal will present a talk on the 
paper "[Pure Operation-Based Replicated Data Types][1]" by Carlos Baquero,
Paulo Sergio Almeida and Ali Shokar.

> Paper abstract: Distributed systems designed to serve clients across the world
> often make use of geo-replication to attain low latency and high
> availability. Conflict-free Replicated Data Types (CRDTs) allow the design of
> predictable multi-master replication and support eventual consistency of
> replicas that are allowed to transiently diverge. CRDTs come in two flavors:
> state-based, where a state is changed locally, shipped and merged into other
> replicas; operation-based, where operations are issued locally and reliably
> causal broadcast to all other replicas. However, standard definition of
> op-based CRDT is very encompassing, allowing even sending the full-state, and
> thus imposing storage and dissemination overheads as well as blurring the
> distinction from state-based CRDTs. Pure Operation-Based CRTDs send only
> operations to other replicas, drawing a clear distinction from state-based
> CRDTs.

Our talk this month will be on Wednesday, January 15, 2020 at 7:00 pm. Our meeting
will be held at Improving, 10111 Richmond Ave, Suite 100, Houston, TX 77042. There
is plenty of free parking in front of the building. [Click here][2] to get directions.

[Click here to RSVP][3]. Please take a moment to RSVP; it really helps us understand
how much food and seating we ought to prepare. Hope to see you there!

[Slides for this talk are now available][4]

[1]: https://hfpug.com/pure_op_based_crdt.pdf
[2]: https://www.google.com/maps/place/10111+Richmond+Ave+%23550,+Houston,+TX+77042/@29.7276881,-95.5536627,17z/data=!3m1!4b1!4m5!3m4!1s0x8640c32f7f4403ef:0x9f415717d58bbb25!8m2!3d29.7276628!4d-95.5514895
[3]: https://www.eventbrite.com/e/houston-functional-programmers-pure-op-based-crdts-tickets-89193053825
[4]: https://hfpug.com/january-2020-pure_ops_crdt.pdf
