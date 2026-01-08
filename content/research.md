+++
date = '2025-12-23T12:38:11Z'
draft = false
title = 'Research'
+++

My research spans three interconnected areas in AI safety and infrastructure:

## 1. Scientist AI: Interpretable World Models Without Agency

**Research Question:** Can we build safer, more interpretable AI through passive causal world model learning?

### The Core Idea

Most AI systems optimize for goals using black-box methods, creating misalignment risks (deceptive alignment, instrumental convergence). What if we remove agency entirely while retaining learning capability? The Scientist AI approach learns interpretable causal world models without goal-seeking behavior.

### My Approach

- Implementing Scientist AI at scale to demonstrate practical tractability
- Developing novel algorithms for causal structure and theory language search
- Empirically characterizing when and where interpretable world models work
- Analyzing safety properties of passive learning systems

### Key Hypothesis

Removing agency (affordances + goal-seeking) while retaining learning capability creates inherently safer AI. No instrumental convergence, no deceptive alignment, interpretable failure modes, verifiable objectives.

---

## 2. Few-Shot Catastrophe Prevention

**Research Question:** When we catch AI misbehavior, what's the best way to use that information?

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

## 3. Infrastructure Sovereignty & Digital Vassalage

**Research Question:** How do nations without economic leverage negotiate fair terms for AI infrastructure in an oligopolistic market?

### The Core Problem

Middle-power nations like the Philippines face a critical strategic choice: adopt AI built entirely on foreign-owned "rented" infrastructure (AWS, Microsoft, Google), or pursue digital sovereignty. This creates a 21st-century form of **Digital Vassalage** where national wealth flows continuously to foreign cloud providers as subscription fees for essential services.

**The Bargaining Asymmetry:** The Philippine government gets worse deals for compute and AI services compared to how the UK negotiates. This pattern extends to all uncompetitive economies - the global AI infrastructure market replicates existing power hierarchies. Wealthy nations with regulatory leverage negotiate favorable terms; smaller economies pay retail prices with no strategic benefits.

**The BPO Constraint:** The Philippines has ~1.3 million jobs in the BPO industry (call centers, back-office services). AI threatens this directly, creating a brutal trilemma:
1. Adopt AI aggressively → unemployment crisis in BPO sector
2. Resist AI adoption → become economically irrelevant
3. Become AI-dependent without infrastructure → permanent vassalage with no control over the tech displacing your workforce

### Research Approach

I'm systematically analyzing the **terms** of AI infrastructure dependency (not just whether it exists):

**Phase 1:** Document what deals are being struck - quantify the cost differential between UK, Philippines, and other middle-power nations

**Phase 2:** Analyze why markets can't fix this - oligopoly + network effects + high switching costs create permanent asymmetry

**Phase 3:** Identify strategic options - what leverage do uncompetitive economies actually have? Hybrid models, regional cooperation (ASEAN), alternative providers, policy creativity

### Why This Matters

As a Filipino AI safety researcher in the UK, I have a dual perspective on these dynamics. This research connects directly to AI safety: global AI safety requires infrastructure equity. Nations without good infrastructure terms can't build domestic AI safety capacity, creating a dangerous concentration of safety research in wealthy nations with existing leverage.

### Output Structure

- **Paper 1:** The Infrastructure Bargaining Gap (documenting the problem)
- **Paper 2:** Why Markets Can't Fix Digital Vassalage (explaining persistence)
- **Paper 3:** Strategic Options for Uncompetitive Economies (practical policy options)
- **Paper 4:** The BPO Trap (Philippines-specific analysis)

---

For technical details and daily progress, see my [research blog](/posts/).
