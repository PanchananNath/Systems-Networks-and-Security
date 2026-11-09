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

- 🎓 [CMU 15-445/645 Database Systems](https://15445.courses.cs.cmu.edu/) — Andy Pavlo · CMU
- 📄 [Architecture of a Database System](https://doi.org/10.1561/1900000002) — Hellerstein, Stonebraker, Hamilton (2007)
- 📘 [Readings in Database Systems (Red Book, free)](http://www.redbook.io/) — Bailis, Hellerstein, Stonebraker
- 📘 [Database Internals](https://www.databass.dev/) — Alex Petrov

<sub>📘 book · 🎓 course · 📄 paper · 📑 spec/standard · 🛠 tool/docs</sub>

## Lab ideas

- Build a toy LSM-tree key-value store
- Compare fsync behaviour across file systems

## Related

- [Distributed Systems](../04-distributed-systems/)

## Notes

Add notes as separate files in this folder (e.g. `notes-<subtopic>.md`) using [`templates/topic-note.md`](../../templates/topic-note.md).
