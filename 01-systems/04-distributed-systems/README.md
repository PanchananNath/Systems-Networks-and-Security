# Distributed Systems

> **Section:** 01 · Systems · **Level:** Advanced

Building reliable systems from unreliable, networked parts.

## Core subjects

- [ ] Time, clocks, ordering (Lamport, vector clocks)
- [ ] Replication, consistency models (linearizability → eventual)
- [ ] Consensus: Paxos, Raft, Byzantine fault tolerance (PBFT)
- [ ] Distributed transactions, 2PC
- [ ] Partitioning, sharding, membership
- [ ] Case studies: GFS, MapReduce, Spanner, Dynamo

## Key references

- Kleppmann — *Designing Data-Intensive Applications*
- Ongaro & Ousterhout — *In Search of an Understandable Consensus Algorithm* (USENIX ATC 2014)
- Lamport — *Paxos Made Simple* (2001)
- MIT 6.5840 (formerly 6.824) — labs and lecture notes

## Lab ideas

- Implement Raft and test it under partitions
- Build a sharded key-value store

## Related

- [Blockchain & DLT Security](../../03-security/07-blockchain-security/)

## Notes

Add notes as separate files in this folder (e.g. `notes-<subtopic>.md`) using [`templates/topic-note.md`](../../templates/topic-note.md).
