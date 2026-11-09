# 5G / B5G Security

> **Section:** 03 · Security · **Level:** Advanced

Security architecture and attack surface of modern cellular networks.

## Core subjects

- [ ] 5G security architecture (3GPP TS 33.501)
- [ ] Authentication: 5G-AKA, EAP-AKA', SUCI/SUPI privacy
- [ ] SBA/API security between network functions
- [ ] Network-slicing isolation
- [ ] Signalling and protocol attacks (NAS/RRC, SS7/Diameter legacy)
- [ ] O-RAN and MEC security
- [ ] Formal verification of cellular protocols

## Key references

- 📑 [3GPP TS 33.501 — Security architecture for the 5G System](https://www.3gpp.org/DynaReport/33501.htm)
- 📄 [A Formal Analysis of 5G Authentication](https://doi.org/10.1145/3243734.3243846) — Basin et al. (CCS 2018)
- 📄 [LTEInspector: Adversarial Testing of 4G LTE](https://doi.org/10.14722/ndss.2018.23313) — Hussain et al. (NDSS 2018)
- 📄 [5GReasoner: Property-Directed Security and Privacy Analysis of 5G](https://doi.org/10.1145/3319535.3354263) — Hussain et al. (CCS 2019)
- 📑 [ENISA Threat Landscape for 5G Networks](https://www.enisa.europa.eu/publications/enisa-threat-landscape-for-5g-networks)
- 🛠 [Tamarin Prover](https://github.com/tamarin-prover/tamarin-prover)

<sub>📘 book · 🎓 course · 📄 paper · 📑 spec/standard · 🛠 tool/docs</sub>

## Lab ideas

- Trace 5G-AKA on an Open5GS + UERANSIM testbed
- Model an authentication flow in Tamarin or ProVerif

## Related

- [Mobile Networks: 4G / 5G / B5G / 6G](../../02-networks/04-mobile-5g-6g/)

## Notes

Add notes as separate files in this folder (e.g. `notes-<subtopic>.md`) using [`templates/topic-note.md`](../../templates/topic-note.md).
