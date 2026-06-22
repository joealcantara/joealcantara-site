+++
date = '2025-12-23T12:38:11Z'
draft = false
title = 'Research'
+++

My research applies psychology and philosophy of mind to AI — asking what AI looks like if we build it the way we know minds actually work, rather than scaling statistical pattern matching. It has narrowed to a single thesis.

## Epistemic Developmental AI

**Curiosity is the hinge.** My research looks at building language models that learn the way children do — driven by curiosity rather than a training objective, grounded in concrete concepts before abstract ones, and growing their own capacity in response to what they cannot yet represent. The idea is that a system built this way recovers the structure that *generates* language and reasoning, rather than its surface statistics. And the same property that makes it learn this way makes it safe.

The claim has two faces, and they are the same property seen twice.

### The learning face

Piaget established that concrete operational thinking precedes formal operational thinking. Vygotsky established that new learning must attach to existing knowledge structures. Pearl established that genuine causal reasoning requires representations at the interventional level. A model built on those principles — grounded initialisation, dependency-ordered curriculum, dynamically growing capacity — should fail less systematically than one trained on statistical co-occurrence alone.

### The safety face

We are building more agentic AI before solving alignment, and the proposed fixes — better goals, better alignment techniques — stay inside the paradigm that created the problem. The alternative is a system structurally incapable of misalignment: one that produces knowledge rather than pursuing goals. A system without goals cannot deceive — there is nothing to hide. This draws on the belief/desire literature (Hume, Dennett), intentionality theory (Searle), and recent AI safety work (Bengio et al.).

Goallessness is the single property that makes a system both learn well and stay safe.

---

For updates and progress, see my [research blog](/posts/).
