# Cryptography

> **Section:** 03 · Security · **Level:** Intermediate → Advanced

The math and engineering of confidentiality, integrity and authenticity.

## Core subjects

- [ ] Symmetric crypto: block ciphers, modes, AEAD
- [ ] Hash functions, MACs, KDFs
- [ ] Public-key: RSA, Diffie-Hellman, elliptic curves
- [ ] Digital signatures, PKI, certificates
- [ ] Protocols: TLS 1.3, Signal, Noise
- [ ] Zero-knowledge proofs, MPC, homomorphic encryption (intro)
- [ ] Post-quantum cryptography (ML-KEM, ML-DSA, SLH-DSA)

## Key references

- 📘 [A Graduate Course in Applied Cryptography (free)](https://toc.cryptobook.us/) — Boneh & Shoup · Stanford/NYU
- 📘 [Introduction to Modern Cryptography, 3rd ed.](https://www.cs.umd.edu/~jkatz/imc.html) — Katz & Lindell
- 🎓 [Cryptography I](https://www.coursera.org/learn/crypto) — Dan Boneh · Stanford
- 📑 [RFC 8446 — TLS 1.3](https://www.rfc-editor.org/rfc/rfc8446)
- 📑 [FIPS 203 (ML-KEM)](https://doi.org/10.6028/NIST.FIPS.203) — NIST post-quantum
- 📑 [FIPS 204 (ML-DSA)](https://doi.org/10.6028/NIST.FIPS.204) — NIST post-quantum
- 📑 [FIPS 205 (SLH-DSA)](https://doi.org/10.6028/NIST.FIPS.205) — NIST post-quantum

<sub>📘 book · 🎓 course · 📄 paper · 📑 spec/standard · 🛠 tool/docs</sub>

## Lab ideas

- Implement and break textbook RSA (small keys, no padding)
- Inspect a TLS 1.3 handshake in Wireshark

## Related

- [Discrete Math, Probability & Linear Algebra](../../00-foundations/02-discrete-math-probability/)

## Notes

Add notes as separate files in this folder (e.g. `notes-<subtopic>.md`) using [`templates/topic-note.md`](../../templates/topic-note.md).
