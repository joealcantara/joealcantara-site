+++
date = '2025-12-23T12:38:11Z'
draft = false
title = 'Research'
+++

My research spans three interconnected areas in AI safety and infrastructure:

## 1. Scientist AI: Interpretable World Models Without Agency

**Research Question:** Can we build safer, more interpretable AI through passive causal world model learning?

### Core Problem

Most AI systems optimize for goals using black-box methods, creating misalignment risks (deceptive alignment, instrumental convergence). What if we remove agency entirely while retaining learning capability? The Scientist AI approach learns interpretable causal world models without goal-seeking behavior - no instrumental convergence, no deceptive alignment, interpretable failure modes, verifiable objectives.

### My Approach

- Implementing Scientist AI at scale to demonstrate practical tractability
- Developing novel algorithms for causal structure and theory language search
- Empirically characterizing when and where interpretable world models work
- Analyzing safety properties of passive learning systems

---

## 2. Few-Shot Catastrophe Prevention

**Research Question:** When we catch AI misbehavior, what's the best way to use that information?

### Core Problem

Current AI safety research often assumes we have massive datasets of examples showing what we want AI systems to avoid. But in practice, we might only catch a handful of catastrophic behaviors before something goes seriously wrong. Can we effectively prevent catastrophes from just a few caught examples?

### My Approach

I'm building systematic benchmarks to compare different prevention techniques:

- **Probes**: Can we detect dangerous patterns from few examples?
- **Fine-tuning**: Does training on caught examples help, or does it teach the model to hide misbehavior?
- **Monitoring**: What's the tradeoff between control and alignment?

---

## 3. Infrastructure Sovereignty & Digital Vassalage

**Research Question:** How do nations without economic leverage negotiate fair terms for AI infrastructure in an oligopolistic market?

### Core Problem

Middle-power nations like the Philippines face a critical strategic choice: adopt AI built entirely on foreign-owned "rented" infrastructure (AWS, Microsoft, Google), or pursue digital sovereignty. This creates a 21st-century form of **Digital Vassalage** where national wealth flows continuously to foreign cloud providers as subscription fees for essential services.

The Philippine government gets worse deals for compute and AI services compared to how the UK negotiates. This pattern extends to all uncompetitive economies - the global AI infrastructure market replicates existing power hierarchies. Wealthy nations with regulatory leverage negotiate favorable terms; smaller economies pay retail prices with no strategic benefits.

The Philippines has ~1.3 million jobs in the BPO industry (call centers, back-office services). AI threatens this directly, creating a brutal trilemma:
1. Adopt AI aggressively → unemployment crisis in BPO sector
2. Resist AI adoption → become economically irrelevant
3. Become AI-dependent without infrastructure → permanent vassalage with no control over the tech displacing your workforce

### My Approach

I'm systematically analyzing the **terms** of AI infrastructure dependency (not just whether it exists). This involves documenting what deals are being struck and quantifying cost differentials between nations, analyzing why markets can't fix bargaining asymmetries in oligopolistic infrastructure markets, and identifying strategic options for uncompetitive economies through hybrid models, regional cooperation, and policy creativity.

---

For technical details and daily progress, see my [research blog](/posts/).
