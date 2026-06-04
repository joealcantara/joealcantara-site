+++
date = '2025-12-23T12:38:11Z'
draft = false
title = 'Research'
+++

My research programme — Psychology-Grounded AI Learning — asks whether grounding AI systems in the principles developmental psychology has established for genuine understanding produces systems that fail less systematically than those trained on statistical co-occurrence alone.

Current AI failures are not incidental. A system that recommends walking to a car wash has no world model. A system that cannot count letters in a word has no grounded structural representation. These failures are predictable architectural consequences of training on static, randomly ordered corpora with fixed architectures — and developmental psychology tells us something about why.

---

## Track 1 — Epistemic vs Instrumental AI

**Research question:** Is the epistemic/instrumental distinction formally coherent, and what safety properties does it guarantee?

The field conflates two categorically different things: systems that *produce knowledge* and systems that *pursue goals*. A system without goals cannot deceive — there is nothing to hide. The safety-relevant failures of AI concentrate in the instrumental category. This track establishes the distinction formally, grounded in the belief/desire literature (Hume, Dennett), intentionality theory (Searle), and recent AI safety work (Bengio et al.).

---

## Track 2 — Memory Architecture and Retrieval Quality

**Research question:** Is context window size the right metric for memory in language models?

Cowan's embedded-processes model establishes that working memory is activated long-term memory, with approximately four chunks in the attentional focus at any moment. The constraint is not buffer size — it is retrieval quality. A chess grandmaster holds four chunks in working memory but navigates decades of pattern knowledge in milliseconds via fast associative retrieval. This track argues for retrieval quality as the primary benchmark dimension and designs a benchmark instrument from six cognitive science dimensions.

---

## Track 3 — Developmental Architecture for Language Models

**Research question:** Does a model whose architecture grows in response to its own representational limits produce different internal structure than a fixed-architecture model trained on the same staged data?

Piaget established that concrete operational thinking precedes formal operational thinking. Vygotsky established that new learning must attach to existing knowledge structures. Pearl established that genuine causal reasoning requires representations at the interventional level. Current training regimes implement none of these principles. This track tests computationally whether they matter — through staged language acquisition experiments in which model capacity grows dynamically rather than being fixed at architecture design time.

---

For updates and progress, see my [research blog](/posts/).
