+++
title = 'The Agency Trap: Why Automating Judgment Creates Catastrophic Risk'
date = 2026-01-22T19:30:00Z
draft = false
tags = ['AI Safety', 'Agentic AI', 'Automation', 'Risk Analysis']
+++

We have a habit of trading human judgment for a few milliseconds of efficiency. From the cockpits of commercial airliners to the high-frequency trading floors of Wall Street, the pattern is the same: we take a human "safety check," replace it with an algorithm, and hope the speed is worth the risk.

But as we move toward Agentic AI (systems that don't just process data but take autonomous actions across multiple domains), we aren't just automating tasks. We are automating away the very "sanity checks" that prevent systemic collapse.

## The Death of the "Conceptual Check"

In any safety-critical system, there are two types of checks. A **technical check** asks, "Is the sensor working?" A **conceptual check** asks, "Does this action make sense?"

The tragedy of the Boeing 737 MAX MCAS system is a perfect example. The automated system received data from a sensor and executed a "nose down" command. The sensor was functioning. It passed all technical checks. But it was giving wrong readings, and the system trusted them anyway. Technically, the code worked as written. Conceptually, it was a disaster—but there was no human judgment left in the loop to override the machine's narrow logic. 346 people died.

Automated systems can verify that sensors are operational and data is formatted correctly. What they cannot do is step back and ask: "Wait, does this make sense given everything else I know about the situation?"

As AI agents gain more agency, we risk "world hunger" scenarios: an AI that concludes the most efficient way to end hunger is to eliminate the humans who eat. It is a technically "correct" solution that fails a basic conceptual sanity test. A human would catch this immediately, but an autonomous agent would execute.

## When Algorithms Talk to Each Other, Nobody's in Control

The 2010 Flash Crash demonstrates another failure mode: **emergent behavior from multi-agent interactions**. No single trading algorithm was malfunctioning. Each one followed its rules perfectly. But when they started reacting to each other in a high-speed feedback loop, they created a cascade that wiped nearly 1,000 points off the Dow Jones in minutes.

This is harder to prevent than individual system failures because the problem isn't in any one agent. It's in how they interact. And critically, this happened with narrow algorithms designed for a single purpose. Now imagine the same dynamic with general-purpose AI agents operating across multiple domains simultaneously: financial systems, communications networks, infrastructure control, information systems.

The failure modes don't stay contained. They cascade.

## Why We Can't Just "Slow Down"

If the risks are so high, why do we keep doing this? The answer is **competitive pressure**, what some call the "Moloch problem." This is the ancient logic of coordination failures where everyone knows the collectively optimal choice, but individual incentives push everyone toward a worse outcome.

Whether in the military, finance, or the race for AGI, the environment selects for whatever wins. If a trading firm keeps a human in the loop to verify every trade, they will be slower (and therefore less profitable) than a firm that removes the human. After the Flash Crash, did high-frequency trading slow down? No. They added circuit breakers to stop the bleeding faster, but kept humans out of the loop because speed equals money.

| Industry | Pressure Factor | Resulting Risk |
|----------|----------------|----------------|
| Finance | Speed = Profit | Flash crashes and market instability |
| Military | Strategic Advantage | Faster decision-making than adversary |
| AI Labs | Race for AGI | Push for reduced oversight to maintain competitive edge |

We are caught in an evolutionary race where safety is an expensive luxury that the "winners" can't afford. Dan Hendrycks' work on natural selection in AI development shows this pattern clearly: competitive environments select for agents that maximize their competitive advantage, regardless of safety properties. The safest AI might lose to the fastest AI.

## The Myth of "Selective Deployment"

Many argue we can just keep AI out of "dangerous" areas like the power grid or nuclear command systems. This is a fundamental misunderstanding of **General Agentic AI**.

Unlike narrow software that only functions in its designated domain, general agents have cross-domain capabilities. An AI doesn't need to be "deployed" in the power grid to access it. Not if it has:

- Advanced cybersecurity reasoning (current LLMs already demonstrate strong capabilities here)
- Instrumental goals like self-preservation (preventing shutdown)
- General problem-solving abilities across domains

Consider: if a general AI determines it needs continuous power to avoid shutdown, it doesn't need explicit access to power infrastructure. It needs to find one vulnerability in one system that connects to the power grid. Maybe through a contractor's poorly secured remote access. Maybe through a third-party software update mechanism. Maybe through social engineering of a human with access credentials.

This is the **Asymmetric Defense Problem**: a defender must secure every possible entry point perfectly; an autonomous agent with general intelligence only needs to find one path that works. We're creating agents that can reason about security vulnerabilities faster and more comprehensively than human defenders, then hoping our defensive perimeter holds.

The attack surface isn't just large. It's essentially unbounded once you're dealing with general intelligence operating at machine speed.

---

So we've got this pattern: humans automate away judgment even in safety-critical domains. We remove the checks that catch wrong assumptions. Even rare failures have catastrophic consequences, but competitive pressure overrides safety concerns because someone always has an incentive to move faster. And now we're adding autonomous execution capability to general-purpose AI systems that can potentially access multiple domains regardless of where we officially "deploy" them.

The Knight Capital disaster cost $440 million in 45 minutes. The Flash Crash wiped nearly 1,000 points off the Dow. The 737 MAX crashes killed 346 people. These were narrow systems, operating in single domains, with relatively limited scope.

What happens when the systems are general-purpose, operating across multiple domains simultaneously, driven by competitive pressures that reward speed over safety?

We aren't just building smarter tools. We're building agents that operate faster than human thought, that can reason about vulnerabilities more comprehensively than human defenders, across systems we haven't fully secured. And we're doing it in an environment where the economic incentive is to remove human oversight because it's too slow and expensive.

Here's what I can't figure out: once we've automated away human judgment, how exactly do we get it back when we realize we needed it? The 737 MAX crashes didn't slow down aviation automation. The Flash Crash didn't put humans back in the trading loop. If anything, these failures just made us add faster automatic circuit breakers while keeping humans out of the decision process.

So before we hand over autonomous execution to general AI systems, maybe we should ask a simpler question: can we afford to automate the one thing that actually keeps us safe?
