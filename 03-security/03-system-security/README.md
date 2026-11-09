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

- Szekeres et al. — *SoK: Eternal War in Memory* (IEEE S&P 2013)
- Costan & Devadas — *Intel SGX Explained* (2016)
- Kocher et al. — *Spectre Attacks* (IEEE S&P 2019)

## Lab ideas

- Fuzz a small C parser with AFL++ or libFuzzer
- Compare a binary with and without hardening flags (`checksec`)

## Related

- [Computer Architecture](../../01-systems/01-computer-architecture/)
- [Operating Systems](../../01-systems/02-operating-systems/)

## Notes

Add notes as separate files in this folder (e.g. `notes-<subtopic>.md`) using [`templates/topic-note.md`](../../templates/topic-note.md).
