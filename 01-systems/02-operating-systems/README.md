# Operating Systems

> **Section:** 01 · Systems · **Level:** Intermediate → Advanced

Abstractions that make hardware usable and safe to share.

## Core subjects

- [ ] Processes, threads, scheduling
- [ ] Virtual memory, paging, page replacement
- [ ] Concurrency: locks, condition variables, lock-free basics
- [ ] File systems, journaling, crash consistency
- [ ] I/O, interrupts, device drivers
- [ ] Kernel internals (Linux), system calls, eBPF

## Key references

- 📘 [Operating Systems: Three Easy Pieces (free)](https://pages.cs.wisc.edu/~remzi/OSTEP/) — Arpaci-Dusseau · UW-Madison
- 🎓 [MIT 6.1810 Operating System Engineering](https://pdos.csail.mit.edu/6.1810/) — MIT PDOS
- 🛠 [xv6 (RISC-V) source](https://github.com/mit-pdos/xv6-riscv) — MIT
- 🛠 [The Linux Kernel documentation](https://docs.kernel.org/)
- 🛠 [eBPF documentation](https://ebpf.io/)

<sub>📘 book · 🎓 course · 📄 paper · 📑 spec/standard · 🛠 tool/docs</sub>

## Lab ideas

- Add a system call to xv6
- Write an eBPF program that traces `execve` calls
- Implement a user-level thread library

## Related

- [Cloud & Virtualization](../05-cloud-virtualization/)

## Notes

Add notes as separate files in this folder (e.g. `notes-<subtopic>.md`) using [`templates/topic-note.md`](../../templates/topic-note.md).
