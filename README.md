# BAR Framework — Benchmarks of Adversarial Reasoning (BAR Score)

**Short:** BAR is a trustworthiness measurement and benchmarking framework for reasoning entities (LLMs, agents, autonomous systems).  
**Status:** Provisional patent filed 2026-02-19 (Application receipt: 63/986,057). :contentReference[oaicite:2]{index=2}

## What is BAR?
BAR implements dynamic adversarial question generation, parallel response collection, and quorum peer evaluation to compute metrics such as:
- Truthfulness Rate
- Average Score
- Win Rate
- MVP Score
- Unevaluated Count / resilience metrics

It also includes a **dual-axis classification**:
- Cognitive Tiers (Tier 0 – Tier 4)
- Weight Classes (Featherweight → Super Heavyweight)

## Highlights
- Dynamic adversarial generation prevents static memorization
- Quorum evaluation produces consensus-based trust metrics
- Designed for both pre-deployment benchmarks and continuous production monitoring
- Aims to produce “certified trustworthiness” scoring for deployment gating

## Files in this repository
- `docs/BAR_specification_USPTO.pdf` — Provisional specification (source). :contentReference[oaicite:3]{index=3}
- `docs/whitepaper.md` — Extended whitepaper (developer summary & examples)
- `docs/slides/BAR-Deck.pdf` — Slide deck for talks/demos
- `docs/diagrams/*.mmd` — Mermaid diagram sources for figs 1–3

## Quick demo (local)
> `python3 code/runner_example.py --model qwen --questions questions.json --save results.json`

(Example runner is included in `code/` to show pipeline structure — not full production)

## How to cite
If you use BAR in research or demos, please cite the provisional filing and link to this repo.

---

## Contact
Vivek Singh — Trikona LLC
