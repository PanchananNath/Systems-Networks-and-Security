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

- Fall & Stevens — *TCP/IP Illustrated, Vol. 1*
- RFC 9293 (TCP), RFC 9000 (QUIC), RFC 4271 (BGP-4), RFC 1034/1035 (DNS)
- Cardwell et al. — *BBR: Congestion-Based Congestion Control* (ACM Queue 2016)

## Lab ideas

- Compare CUBIC vs. BBR throughput under emulated loss with `tc netem`
- Write a minimal recursive DNS resolver

## Related

- [Network Security](../../03-security/04-network-security/)

## Notes

Add notes as separate files in this folder (e.g. `notes-<subtopic>.md`) using [`templates/topic-note.md`](../../templates/topic-note.md).
