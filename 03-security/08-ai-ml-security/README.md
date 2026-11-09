# AI / ML Security

> **Section:** 03 · Security · **Level:** Advanced

Attacks on ML systems and ML-based defences.

## Core subjects

- [ ] Adversarial examples (evasion)
- [ ] Data poisoning and backdoors
- [ ] Privacy attacks: membership inference, model inversion
- [ ] Model extraction
- [ ] LLM security: prompt injection, jailbreaks, agent security
- [ ] ML for intrusion and malware detection

## Key references

- 📄 [Intriguing Properties of Neural Networks](https://arxiv.org/abs/1312.6199) — Szegedy et al. (ICLR 2014)
- 📄 [Explaining and Harnessing Adversarial Examples](https://arxiv.org/abs/1412.6572) — Goodfellow et al. (ICLR 2015)
- 📄 [Towards Evaluating the Robustness of Neural Networks](https://arxiv.org/abs/1608.04644) — Carlini & Wagner (IEEE S&P 2017)
- 📄 [Towards Deep Learning Models Resistant to Adversarial Attacks](https://arxiv.org/abs/1706.06083) — Madry et al. (ICLR 2018)
- 📄 [Membership Inference Attacks Against ML Models](https://arxiv.org/abs/1610.05820) — Shokri et al. (IEEE S&P 2017)
- 📄 [Indirect Prompt Injection](https://arxiv.org/abs/2302.12173) — Greshake et al. (2023)
- 📑 [MITRE ATLAS](https://atlas.mitre.org/)
- 🛠 [Adversarial Robustness Toolbox](https://github.com/Trusted-AI/adversarial-robustness-toolbox)

<sub>📘 book · 🎓 course · 📄 paper · 📑 spec/standard · 🛠 tool/docs</sub>

## Lab ideas

- Run FGSM/PGD against a small classifier and evaluate defences
- Train an IDS on a public dataset and test it on adversarially perturbed flows

## Related

- [AI / ML for Networking](../../02-networks/08-ai-for-networking/)

## Notes

Add notes as separate files in this folder (e.g. `notes-<subtopic>.md`) using [`templates/topic-note.md`](../../templates/topic-note.md).
