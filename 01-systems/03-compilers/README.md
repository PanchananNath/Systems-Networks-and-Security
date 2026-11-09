# Compilers & ML Compilers

> **Section:** 01 · Systems · **Level:** Advanced

From source (or a neural network) to efficient machine code.

## Core subjects

- [ ] Lexing, parsing, ASTs, semantic analysis
- [ ] IRs, SSA form, data-flow analysis
- [ ] Optimisations: inlining, loop transformations, vectorisation
- [ ] Code generation, register allocation
- [ ] LLVM: passes, IR, backends
- [ ] MLIR: dialects, lowering, pattern rewriting
- [ ] ML compilers: TVM, IREE, XLA; TinyML deployment

## Key references

- Cooper & Torczon — *Engineering a Compiler*
- Lattner et al. — *MLIR: Scaling Compiler Infrastructure for Domain Specific Computation* (CGO 2021)
- Chen et al. — *TVM: An Automated End-to-End Optimizing Compiler for Deep Learning* (OSDI 2018)
- llvm.org/docs and mlir.llvm.org

## Lab ideas

- Write an LLVM pass that counts instructions per function
- Write an MLIR pass that extracts per-layer op/FLOP statistics from a model
- Lower a small PyTorch model through an ML compiler and compare latency

## Related

- [Embedded Systems, Edge & TinyML](../07-embedded-edge-tinyml/)

## Notes

Add notes as separate files in this folder (e.g. `notes-<subtopic>.md`) using [`templates/topic-note.md`](../../templates/topic-note.md).
