# Computer Architecture

> **Section:** 01 · Systems · **Level:** Intermediate

How hardware executes software — the base for performance, compilers and side-channel security.

## Core subjects

- [ ] ISA design (x86-64, ARM, RISC-V)
- [ ] Pipelining, hazards, out-of-order and speculative execution
- [ ] Memory hierarchy: caches, coherence, TLBs, DRAM
- [ ] Multicore, consistency models
- [ ] GPUs and domain-specific accelerators (TPUs, NPUs)

## Key references

- 📘 [Computer Architecture: A Quantitative Approach, 7th ed.](https://shop.elsevier.com/books/computer-architecture/hennessy/978-0-443-15406-5) — Hennessy, Patterson, Kozyrakis
- 📘 [Computer Organization and Design, RISC-V Edition, 2nd ed.](https://shop.elsevier.com/books/computer-organization-and-design-risc-v-edition/patterson/978-0-12-820331-6) — Patterson & Hennessy
- 🎓 [Computer Architecture (lectures + videos)](https://safari.ethz.ch/architecture/) — Onur Mutlu · ETH Zürich
- 🎓 [MIT 6.823 Computer System Architecture](https://ocw.mit.edu/courses/6-823-computer-system-architecture-fall-2005/) — MIT OpenCourseWare
- 🛠 [gem5 simulator](https://github.com/gem5/gem5)

<sub>📘 book · 🎓 course · 📄 paper · 📑 spec/standard · 🛠 tool/docs</sub>

## Lab ideas

- Measure cache-line size and cache levels with a pointer-chasing benchmark
- Simulate a 5-stage RISC-V pipeline (e.g., in gem5 or a custom simulator)

## Related

- [System & Software Security](../../03-security/03-system-security/)

## Notes

Add notes as separate files in this folder (e.g. `notes-<subtopic>.md`) using [`templates/topic-note.md`](../../templates/topic-note.md).
