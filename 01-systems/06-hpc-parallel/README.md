# HPC & Parallel Computing

> **Section:** 01 · Systems · **Level:** Intermediate → Advanced

Using many cores, nodes and GPUs at once.

## Core subjects

- [ ] Parallel models: shared memory vs. message passing
- [ ] OpenMP, MPI
- [ ] GPU programming: CUDA, memory coalescing, occupancy
- [ ] Job schedulers: SLURM, PBS
- [ ] Scaling laws (Amdahl, Gustafson), profiling at scale

## Key references

- 📘 [Programming Massively Parallel Processors, 4th ed.](https://shop.elsevier.com/books/programming-massively-parallel-processors/hwu/978-0-323-91231-0) — Hwu, Kirk, El Hajj · UIUC/NVIDIA
- 🛠 [CUDA Programming Guide](https://docs.nvidia.com/cuda/cuda-programming-guide/index.html) — NVIDIA
- 📑 [MPI Standard](https://www.mpi-forum.org/) — MPI Forum
- 🛠 [HPC tutorials (MPI, OpenMP, Pthreads)](https://hpc.llnl.gov/documentation/tutorials) — Lawrence Livermore National Laboratory
- 🛠 [Slurm documentation](https://slurm.schedmd.com/documentation.html)

<sub>📘 book · 🎓 course · 📄 paper · 📑 spec/standard · 🛠 tool/docs</sub>

## Lab ideas

- Parallelise matrix multiply with OpenMP, MPI and CUDA; compare
- Write a SLURM job template for GPU training with checkpointing

## Notes

Add notes as separate files in this folder (e.g. `notes-<subtopic>.md`) using [`templates/topic-note.md`](../../templates/topic-note.md).
