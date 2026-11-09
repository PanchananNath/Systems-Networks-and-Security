# Internet Protocols

> **Section:** 02 · Networks · **Level:** Intermediate

The protocols the Internet actually runs on.

## Core subjects

- [ ] TCP in depth: congestion control (Reno, CUBIC, BBR)
- [ ] QUIC and HTTP/3
- [ ] BGP and inter-domain routing
- [ ] DNS, DNSSEC
- [ ] TLS as a transport-layer protocol

## Key references

- 📑 [RFC 9293 — Transmission Control Protocol](https://www.rfc-editor.org/rfc/rfc9293)
- 📑 [RFC 9000 — QUIC](https://www.rfc-editor.org/rfc/rfc9000)
- 📑 [RFC 9114 — HTTP/3](https://www.rfc-editor.org/rfc/rfc9114)
- 📑 [RFC 4271 — BGP-4](https://www.rfc-editor.org/rfc/rfc4271)
- 📑 [RFC 1034 / RFC 1035 — DNS](https://www.rfc-editor.org/rfc/rfc1035)
- 📄 [Congestion Avoidance and Control](https://doi.org/10.1145/52325.52356) — Jacobson (SIGCOMM 1988)
- 📄 [BBR: Congestion-Based Congestion Control](https://queue.acm.org/detail.cfm?id=3022184) — Cardwell et al. (ACM Queue 2016)

<sub>📘 book · 🎓 course · 📄 paper · 📑 spec/standard · 🛠 tool/docs</sub>

## Lab ideas

- Compare CUBIC vs. BBR throughput under emulated loss with `tc netem`
- Write a minimal recursive DNS resolver

## Related

- [Network Security](../../03-security/04-network-security/)

## Notes

Add notes as separate files in this folder (e.g. `notes-<subtopic>.md`) using [`templates/topic-note.md`](../../templates/topic-note.md).
