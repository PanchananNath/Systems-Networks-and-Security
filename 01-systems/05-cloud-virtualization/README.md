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

- Barham et al. — *Xen and the Art of Virtualization* (SOSP 2003)
- Verma et al. — *Large-scale cluster management at Google with Borg* (EuroSys 2015)
- kubernetes.io documentation

## Lab ideas

- Build a container from scratch with `unshare` and cgroups
- Deploy a 3-node Kubernetes cluster (kind/k3s) and break it on purpose

## Related

- [Data Center Networking](../../02-networks/06-datacenter-networking/)

## Notes

Add notes as separate files in this folder (e.g. `notes-<subtopic>.md`) using [`templates/topic-note.md`](../../templates/topic-note.md).
