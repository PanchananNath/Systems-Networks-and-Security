# Storage & Database Internals

> **Section:** 01 · Systems · **Level:** Intermediate → Advanced

How data is laid out, indexed, and kept consistent.

## Core subjects

- [ ] Storage devices: HDD, SSD/flash, NVMe
- [ ] Indexes: B+-trees, LSM-trees
- [ ] Query processing and optimisation
- [ ] Transactions, concurrency control, recovery (WAL, ARIES)
- [ ] Distributed databases

## Key references

- Petrov — *Database Internals*
- Hellerstein, Stonebraker, Hamilton — *Architecture of a Database System* (2007)
- CMU 15-445/645 — lectures and BusTub labs

## Lab ideas

- Build a toy LSM-tree key-value store
- Compare fsync behaviour across file systems

## Related

- [Distributed Systems](../04-distributed-systems/)

## Notes

Add notes as separate files in this folder (e.g. `notes-<subtopic>.md`) using [`templates/topic-note.md`](../../templates/topic-note.md).
