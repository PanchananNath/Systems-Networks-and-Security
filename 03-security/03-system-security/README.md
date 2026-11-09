# System & Software Security

> **Section:** 03 · Security · **Level:** Advanced

Security of programs, operating systems and hardware.

## Core subjects

- [ ] Memory-safety bugs and mitigations (stack canaries, ASLR, DEP, CFI)
- [ ] OS security: isolation, sandboxing, capabilities, SELinux
- [ ] Trusted execution: SGX, TrustZone, confidential VMs
- [ ] Secure boot, measured boot, TPM
- [ ] Micro-architectural side channels (Spectre, Meltdown)
- [ ] Fuzzing, static and dynamic analysis

## Key references

- 🎓 [MIT 6.5660 Computer Systems Security](https://ocw.mit.edu/courses/6-5660-computer-systems-security-spring-2024/) — MIT OpenCourseWare
- 📄 [SoK: Eternal War in Memory](https://doi.org/10.1109/SP.2013.13) — Szekeres et al. (IEEE S&P 2013)
- 📄 [Control-Flow Integrity](https://doi.org/10.1145/1102120.1102165) — Abadi et al. (CCS 2005)
- 📄 [Intel SGX Explained](https://eprint.iacr.org/2016/086) — Costan & Devadas (2016)
- 📄 [Spectre Attacks: Exploiting Speculative Execution](https://doi.org/10.1109/SP.2019.00002) — Kocher et al. (IEEE S&P 2019)
- 📄 [Meltdown: Reading Kernel Memory from User Space](https://www.usenix.org/conference/usenixsecurity18/presentation/lipp) — Lipp et al. (USENIX Security 2018)
- 🛠 [AFL++ fuzzer](https://github.com/AFLplusplus/AFLplusplus)

<sub>📘 book · 🎓 course · 📄 paper · 📑 spec/standard · 🛠 tool/docs</sub>

## Lab ideas

- Fuzz a small C parser with AFL++ or libFuzzer
- Compare a binary with and without hardening flags (`checksec`)

## Related

- [Computer Architecture](../../01-systems/01-computer-architecture/)
- [Operating Systems](../../01-systems/02-operating-systems/)

## Notes

Add notes as separate files in this folder (e.g. `notes-<subtopic>.md`) using [`templates/topic-note.md`](../../templates/topic-note.md).
