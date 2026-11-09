# Systems, Networks & Security

A structured, open knowledge base for **study, research and development** across computer systems, networking and security — from foundations to research frontiers, with runnable labs.

> Notes, reading lists and labs are curated as I study and research. Contributions and corrections are welcome — see [CONTRIBUTING.md](./CONTRIBUTING.md).

## How this repo is organised

```
.
├── 00-foundations/   Prerequisites: DSA, math, programming, Linux & Git
├── 01-systems/       Architecture, OS, compilers, distributed, cloud, HPC, embedded/TinyML
├── 02-networks/      Fundamentals, protocols, SDN/NFV, 5G/6G, IoT, data center, AI-for-networking
├── 03-security/      Crypto, system, network, web, 5G, blockchain, AI/ML, IoT, forensics
├── 04-research/      Paper notes, reading lists, venues, datasets, research methods
├── 05-labs/          Hands-on, reproducible labs (each with its own README)
├── 06-tools/         Cheat sheets, scripts and configs
├── resources/        Books and free courses
└── templates/        Templates for topic notes, paper notes and labs
```

Every topic folder has the same shape: **overview → core subjects (checklist) → key references → lab ideas → related topics → notes**.

## Contents

- **[00 · Foundations](./00-foundations/)**
  - [Data Structures & Algorithms](./00-foundations/01-data-structures-algorithms/)
  - [Discrete Math, Probability & Linear Algebra](./00-foundations/02-discrete-math-probability/)
  - [Programming: C, Rust, Python, C++](./00-foundations/03-programming/)
  - [Linux, Shell & Git](./00-foundations/04-linux-shell-git/)
- **[01 · Systems](./01-systems/)**
  - [Computer Architecture](./01-systems/01-computer-architecture/)
  - [Operating Systems](./01-systems/02-operating-systems/)
  - [Compilers & ML Compilers](./01-systems/03-compilers/)
  - [Distributed Systems](./01-systems/04-distributed-systems/)
  - [Cloud & Virtualization](./01-systems/05-cloud-virtualization/)
  - [HPC & Parallel Computing](./01-systems/06-hpc-parallel/)
  - [Embedded Systems, Edge & TinyML](./01-systems/07-embedded-edge-tinyml/)
  - [Storage & Database Internals](./01-systems/08-storage-databases/)
  - [Performance Engineering](./01-systems/09-performance-engineering/)
- **[02 · Networks](./02-networks/)**
  - [Networking Fundamentals](./02-networks/01-fundamentals/)
  - [Internet Protocols](./02-networks/02-internet-protocols/)
  - [SDN, NFV & Programmable Networks](./02-networks/03-sdn-nfv/)
  - [Mobile Networks: 4G / 5G / B5G / 6G](./02-networks/04-mobile-5g-6g/)
  - [Wireless & IoT Networking](./02-networks/05-wireless-iot/)
  - [Data Center Networking](./02-networks/06-datacenter-networking/)
  - [Measurement, Emulation & Simulation](./02-networks/07-measurement-simulation/)
  - [AI / ML for Networking](./02-networks/08-ai-for-networking/)
- **[03 · Security](./03-security/)**
  - [Security Foundations](./03-security/01-foundations/)
  - [Cryptography](./03-security/02-cryptography/)
  - [System & Software Security](./03-security/03-system-security/)
  - [Network Security](./03-security/04-network-security/)
  - [Web & Application Security](./03-security/05-web-application-security/)
  - [5G / B5G Security](./03-security/06-5g-b5g-security/)
  - [Blockchain & DLT Security](./03-security/07-blockchain-security/)
  - [AI / ML Security](./03-security/08-ai-ml-security/)
  - [IoT & Embedded Security](./03-security/09-iot-embedded-security/)
  - [Forensics, Malware Analysis & Incident Response](./03-security/10-forensics-malware-ir/)
  - [CTF & Hands-on Practice](./03-security/11-ctf-practice/)
- **[04 · Research](./04-research/)** — paper notes, reading lists, [venues](./04-research/venues.md), [datasets](./04-research/datasets.md)
- **[05 · Labs](./05-labs/)** — reproducible hands-on exercises
- **[06 · Tools](./06-tools/)** — cheat sheets and scripts
- **[Resources](./resources/)** — books and courses

## How to use it

| Goal | Start here |
|---|---|
| **Study** | Follow the *Suggested learning path* in each section README and tick off the checklists. |
| **Research** | Use [04-research](./04-research/) — paper-note template, venue list, reading lists per area. |
| **Development** | Pick a lab in [05-labs](./05-labs/) or a *Lab ideas* item from any topic and build it. |

See [ROADMAP.md](./ROADMAP.md) for what is being filled in next.

## About the references

References are limited to standard textbooks, courses from top universities (MIT, Stanford, CMU, Berkeley, ETH, Harvard, Princeton…), peer-reviewed papers from top venues, and official specifications. Papers link to their DOI, arXiv or publisher page; tools link to their official repository.

Each reference is tagged: 📘 book · 🎓 course · 📄 paper · 📑 spec/standard · 🛠 tool/docs

A [link-check workflow](./.github/workflows/link-check.yml) tests every link on each push and every Monday, so dead links get caught.

## Responsible use

Security material here is for **education and authorised testing only**. See [SECURITY.md](./SECURITY.md).

## License

- **Code** (labs, scripts, tools): [MIT](./LICENSE)
- **Written content** (notes, guides, reading lists): [CC BY 4.0](./LICENSE-CONTENT.md)
