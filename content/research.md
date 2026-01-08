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

**Research Question:** Can nations achieve "Sovereign AI" without owning the physical or cloud infrastructure?

### The Core Problem

Middle-power nations like the Philippines face a critical strategic choice: adopt AI built entirely on foreign-owned "rented" infrastructure (AWS, Microsoft, Google), or pursue digital sovereignty. This creates a 21st-century form of Digital Vassalage where national wealth flows continuously to foreign cloud providers as subscription fees for essential services.

### Comparative Analysis

**UK Model (Tiered Sovereignty):**
- Cybersecurity and Resilience Bill regulates data centers as critical infrastructure
- Retains control over critical nodes while using foreign cloud providers
- Strategic adaptation with policy guardrails

**Philippines Model (Client-State):**
- National AI Strategy 2.0 built on complete cloud dependency
- No domestic data center infrastructure for critical systems
- Pure dependency on foreign triopoly

### Key Themes

- **Infrastructure as Territory:** Data centers and GPU clusters as the "new land" of the intelligence economy
- **Cloud Rent-Seeking:** Continuous extraction of national wealth as subscription fees
- **Strategic Adaptation:** Policy options for middle-power nations navigating the "compute trap"

### Research Approach

Examining how the UK's regulatory approach (2024-2028) compares with the Philippines' dependency model to identify policy guardrails and strategic options for developing nations in the AI era.

---

For technical details and daily progress, see my [research blog](/posts/).
