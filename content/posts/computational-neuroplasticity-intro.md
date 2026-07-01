+++
date = '2026-07-01'
draft = false
title = 'Adventures in Computational Neuroplasticity: Intro'
summary = "Why I'm running a series of small experiments that rebuild the brain's plasticity mechanisms in code — one at a time, honestly, then combined. A map of where this is going."
tags = ['neuroplasticity', 'developmental-ai', 'research', 'notes']
+++

> Draft. This is the opening note for a series — a public logbook of experiments,
> written as I go.

<!-- EDIT: your opening. A sentence on why you're doing this in the open — the
     logbook spirit — sets the tone for everything that follows. -->

Your brain is not quite the same shape it was this morning. As you learn, it
physically rewires itself: connections between neurons strengthen with use and fade
without it, new ones form, and unused ones are quietly cut away. A child's brain does
this dramatically — building far more connections than it could ever need, then
pruning them down to the ones that earn their place. This constant self-rebuilding is
called **neuroplasticity**, and it's a big part of how minds actually develop.

The artificial neural networks behind modern AI mostly *don't* do this. Their
structure is chosen by a human, fixed before training begins, and never changes. They
can adjust the strength of their connections, but they can't grow a new one, and they
can't decide that part of themselves is unnecessary and remove it.

This series is me taking that gap seriously and asking: **what if they could?** I'm
going to rebuild the brain's plasticity mechanisms in code, one at a time, on problems
small enough to see clearly — and write up what happens, honestly, including the parts
where it turns out someone worked it out decades ago. Think lab notebook, not journal
paper: the point is the reasoning, done in the open.

## The two mechanisms this series cares about

Neuroplasticity isn't a single thing — it's a family. Two members matter most here:

- **Synaptic plasticity** — changing the *strength* of existing connections. When a
  connection is used, it strengthens; when it isn't, it fades. This is the closest
  biological cousin to what training does to a neural network's weights.
- **Structural plasticity** — changing the *wiring itself*: growing new neurons and
  connections, and pruning ones that aren't pulling their weight. The architecture is
  not fixed; it is built and rebuilt in response to demand.

Modern AI has a crude version of the first and almost none of the second. Of the two,
structural plasticity — the wiring — is the one it most lacks, and arguably where the
interesting developmental story lives. It's where this series starts.

*(A note on the name: "computational plasticity" already means something else — the
mechanics of how metals deform. I mean **neuroplasticity**, implemented
computationally. Different field, same word.)*

## The method: replicate, validate, then combine

The plan is deliberately unglamorous, and that's the point.

1. **Replicate** one plasticity mechanism at a time, in the simplest setting where it
   can be seen clearly — often a toy problem where the *right answer is already known*,
   so a result can be checked against ground truth instead of guessed at.
2. **Validate** it against what's already known — name the prior work, reproduce the
   established result, and be honest about what's a rediscovery versus what's new.
3. **Combine** the mechanisms. This is where the actual contribution lives: individual
   plasticity mechanisms are well studied in isolation, but the brain runs them
   *together*, and their interaction is far less charted. Composing them — and showing
   what the combination buys — is the real work.

Each post is one rung on that ladder.

## Why I care: capacity that grows in response to need

<!-- EDIT: THIS section is the thesis, and it should be entirely in your voice. The
     draft below paraphrases your profile page — rewrite it as *you* would pitch it to
     a supervisor. Curiosity-driven learning, concrete-before-abstract, goallessness
     as the safety property. Make it yours. -->

My research is about building AI that learns the way minds actually form
understanding: driven by curiosity rather than a fixed training objective, grounded in
concrete concepts before abstract ones, and — the part these experiments speak to —
**growing its own capacity in response to what it cannot yet represent**, rather than
being handed a fixed architecture up front.

That last idea *is* structural plasticity. A system that adds capacity when it hits a
representational limit, and sheds what it doesn't need, is doing in code what a
developing brain does in tissue. If a model built this way recovers the structure that
*generates* language and reasoning rather than its surface statistics — and if, by
only ever seeking to understand, it pursues no goal of its own to misalign — then the
developmental route isn't just a nice story about learning. It's also a safety
argument. These experiments are where I test whether the mechanisms actually behave
the way the story needs them to.

## The roadmap

- **Part 1 — Structural plasticity.** Growing and pruning. Can a network build itself
  down to the smallest solution for a task, more reliably than one designed at that
  size from the start? *(First one's up.)*
- **Part 2 — Synaptic plasticity.** Local learning rules — Hebbian, homeostatic — as
  an alternative to backprop for tuning connection strengths. (Part 1 ends on a loose
  thread that leads straight here.)
- **Later — Combination.** The mechanisms running together, and what the interaction
  produces that neither does alone.

<!-- EDIT: sign-off. An invitation to follow along, or a line on what you'll consider
     a success for the series. -->

Corrections and "you've reinvented X" emails are welcome — that's rather the point of
doing this in the open.
