# Cloud & Virtualization

> **Section:** 01 · Systems · **Level:** Intermediate

Sharing machines safely and elastically.

## Core subjects

- [ ] Hypervisors (KVM, Xen), hardware virtualization support
- [ ] Containers: namespaces, cgroups, images
- [ ] Orchestration: Kubernetes architecture
- [ ] Serverless and microVMs (Firecracker)
- [ ] Cloud networking and storage services

## Key references

- 📄 [Xen and the Art of Virtualization](https://doi.org/10.1145/945445.945462) — Barham et al. (SOSP 2003)
- 📄 [Large-scale cluster management at Google with Borg](https://doi.org/10.1145/2741948.2741964) — Verma et al. (EuroSys 2015)
- 📄 [Firecracker: Lightweight Virtualization for Serverless Applications](https://www.usenix.org/conference/nsdi20/presentation/agache) — Agache et al. (NSDI 2020)
- 🛠 [Kubernetes documentation](https://kubernetes.io/docs/home/)

<sub>📘 book · 🎓 course · 📄 paper · 📑 spec/standard · 🛠 tool/docs</sub>

## Lab ideas

- Build a container from scratch with `unshare` and cgroups
- Deploy a 3-node Kubernetes cluster (kind/k3s) and break it on purpose

## Related

- [Data Center Networking](../../02-networks/06-datacenter-networking/)

## Notes

Add notes as separate files in this folder (e.g. `notes-<subtopic>.md`) using [`templates/topic-note.md`](../../templates/topic-note.md).
