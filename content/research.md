+++
date = '2025-12-23T12:38:11Z'
draft = false
title = 'Research'
+++

My research applies psychology and philosophy of mind to AI — asking what AI looks like if we build it the way we know minds actually work, rather than scaling statistical pattern matching.

The three tracks below are three different applications of that frame: what kind of AI is safe (Track 1), how AI should handle knowledge (Track 2), and how AI should learn (Track 3).

---

## Track 1 — Epistemic vs Instrumental AI

**The problem:** We are building more agentic AI before solving alignment. The proposed solutions — better goals, better alignment techniques — remain within the paradigm that caused the problem. The alternative is a category of AI that is structurally incapable of misalignment.

**Central question:** Does the absence of agency and goals in an epistemic system provide structural safety guarantees that aligned instrumental systems cannot?

The field conflates two categorically different things: systems that *produce knowledge* and systems that *pursue goals*. A system without goals cannot deceive — there is nothing to hide. This track establishes the distinction formally, grounded in the belief/desire literature (Hume, Dennett), intentionality theory (Searle), and recent AI safety work (Bengio et al.).

---

## Track 2 — Memory Architecture and Retrieval Quality

**The problem:** The field is treating memory as a buffer-size problem — expanding context windows. Cognitive psychology tells us the constraint is not buffer size; it is retrieval quality.

**Central question:** Is retrieval quality from a well-organised long-term store the right metric for evaluating memory in LLMs — and what does that benchmark look like?

Cowan's embedded-processes model establishes that working memory is activated long-term memory, with approximately four chunks in the attentional focus at any moment. A chess grandmaster holds four chunks in working memory but navigates decades of pattern knowledge in milliseconds via fast associative retrieval. This track argues for retrieval quality as the primary benchmark dimension and designs a benchmark instrument from six cognitive science dimensions.

---

## Track 3 — Developmental Architecture for Language Models

**The problem:** Current LLMs fail systematically — not randomly — because they learn without developmental structure. No grounded foundation, no conceptual dependency ordering, no capacity that grows with understanding. Humans do not brute-force learning; we build hierarchically on what we already know.

**Central question:** Does imposing developmental structure — grounded initialisation, dependency-ordered curriculum, dynamically growing capacity — produce models with more genuine understanding than scale alone?

Piaget established that concrete operational thinking precedes formal operational thinking. Vygotsky established that new learning must attach to existing knowledge structures. Pearl established that genuine causal reasoning requires representations at the interventional level. This track tests computationally whether implementing those principles produces models that fail less systematically than those trained on statistical co-occurrence alone.

---

For updates and progress, see my [research blog](/posts/).
