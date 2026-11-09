# Research methods

## Reading a paper (three passes)

1. **5–10 min:** title, abstract, intro, section headings, conclusion. Decide whether to continue.
2. **~1 hour:** figures, evaluation, key claims. Note what you don't understand.
3. **Deep:** re-derive the key idea; think about how you would have done it differently.

## Experiments

- Fix and record versions (OS, kernel, compiler, library, hardware).
- Repeat runs; report mean ± std or confidence intervals, not single numbers.
- Script everything — a result that can't be regenerated with one command doesn't count.
- Keep raw data; plots are generated from it.

## Writing

- One-sentence contribution first; everything else supports it.
- Every claim in the abstract needs a matching result in the evaluation.
- Threats to validity and limitations are a section, not an afterthought.

## Reproducibility checklist

- [ ] Code public with a README and licence
- [ ] Exact environment (Dockerfile / `requirements.txt` / `environment.yml`)
- [ ] Data or a script to fetch it
- [ ] A single script that regenerates every figure and table
