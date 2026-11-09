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

- Grama et al. — *Introduction to Parallel Computing*
- Hwu, Kirk, El Hajj — *Programming Massively Parallel Processors*
- NVIDIA CUDA C++ Programming Guide; mpi-forum.org

## Lab ideas

- Parallelise matrix multiply with OpenMP, MPI and CUDA; compare
- Write a SLURM job template for GPU training with checkpointing

## Notes

Add notes as separate files in this folder (e.g. `notes-<subtopic>.md`) using [`templates/topic-note.md`](../../templates/topic-note.md).
