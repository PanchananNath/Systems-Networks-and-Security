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

- 📘 [Designing Data-Intensive Applications](https://dataintensive.net/) — Martin Kleppmann
- 🎓 [MIT 6.5840 Distributed Systems](https://pdos.csail.mit.edu/6.824/) — MIT PDOS
- 📄 [Time, Clocks, and the Ordering of Events](https://doi.org/10.1145/359545.359563) — Lamport (CACM 1978)
- 📄 [Paxos Made Simple](https://lamport.azurewebsites.net/pubs/paxos-simple.pdf) — Lamport (2001)
- 📄 [In Search of an Understandable Consensus Algorithm (Raft)](https://www.usenix.org/conference/atc14/technical-sessions/presentation/ongaro) — Ongaro & Ousterhout (USENIX ATC 2014)
- 📄 [Practical Byzantine Fault Tolerance](https://pmg.csail.mit.edu/papers/osdi99.pdf) — Castro & Liskov (OSDI 1999)

<sub>📘 book · 🎓 course · 📄 paper · 📑 spec/standard · 🛠 tool/docs</sub>

## Lab ideas

- Implement Raft and test it under partitions
- Build a sharded key-value store

## Related

- [Blockchain & DLT Security](../../03-security/07-blockchain-security/)

## Notes

Add notes as separate files in this folder (e.g. `notes-<subtopic>.md`) using [`templates/topic-note.md`](../../templates/topic-note.md).
