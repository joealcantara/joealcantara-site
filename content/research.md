+++
date = '2025-12-23T12:38:11Z'
draft = false
title = 'Research'
+++

## Few-Shot Catastrophe Prevention

My research explores a critical question in AI safety: **When we catch AI misbehavior, what's the best way to use that information?**

### The Core Problem

Current AI safety research often assumes we have massive datasets of examples showing what we want AI systems to avoid. But in practice, we might only catch a handful of catastrophic behaviors before something goes seriously wrong.

**The question:** Can we effectively prevent catastrophes from just a few caught examples?

### Research Approach

I'm building systematic benchmarks to compare different prevention techniques:

- **Probes**: Can we detect dangerous patterns from few examples?
- **Fine-tuning**: Does training on caught examples help, or does it teach the model to hide misbehavior?
- **Monitoring**: What's the tradeoff between control and alignment?

### The 4-Paper Arc

| Paper | Core Question | Status |
|-------|---------------|--------|
| **Paper 1** | Can we systematically evaluate prevention techniques? | Active (v0.1 planning) |
| **Paper 2** | How many caught examples do probes actually need? | Ideas only |
| **Paper 3** | Does fine-tuning help alignment or teach hiding? | Ideas only |
| **Paper 4** | What should labs actually do in practice? | Ideas only |

### Validation

This research direction was validated through pilot studies in December 2025:

- **Psychometric Variance Pilot**: Falsified initial hypothesis (r = -0.29, p = 0.49), saving years on a dead-end direction
- **Catastrophe Prevention Pilot**: GO decision - benchmark produces meaningful signal (Baseline: 32%, Probe: 32% failed, Fine-tune: 18% succeeded)

### One-Line Pitch

*"When we catch AI misbehavior, what's the best way to use that information? I'm building a benchmark to compare techniques and found that [results TBD]."*

---

For technical details and daily progress, see my [research blog](/posts/).
