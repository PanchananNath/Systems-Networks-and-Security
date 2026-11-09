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

- 📘 [Engineering a Compiler, 3rd ed.](https://shop.elsevier.com/books/engineering-a-compiler/cooper/978-0-12-815412-0) — Cooper & Torczon · Rice
- 🎓 [Stanford CS143 Compilers](https://web.stanford.edu/class/cs143/) — Stanford
- 📄 [MLIR: A Compiler Infrastructure for the End of Moore's Law](https://arxiv.org/abs/2002.11054) — Lattner et al. (CGO 2021)
- 📄 [TVM: An Automated End-to-End Optimizing Compiler for Deep Learning](https://www.usenix.org/conference/osdi18/presentation/chen) — Chen et al. (OSDI 2018)
- 🛠 [LLVM documentation](https://llvm.org/docs/)
- 🛠 [MLIR documentation](https://mlir.llvm.org/)
- 🛠 [IREE](https://github.com/iree-org/iree)

<sub>📘 book · 🎓 course · 📄 paper · 📑 spec/standard · 🛠 tool/docs</sub>

## Lab ideas

- Write an LLVM pass that counts instructions per function
- Write an MLIR pass that extracts per-layer op/FLOP statistics from a model
- Lower a small PyTorch model through an ML compiler and compare latency

## Related

- [Embedded Systems, Edge & TinyML](../07-embedded-edge-tinyml/)

## Notes

Add notes as separate files in this folder (e.g. `notes-<subtopic>.md`) using [`templates/topic-note.md`](../../templates/topic-note.md).
