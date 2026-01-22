+++
title = 'The Agency Trap: Why Automating Judgment Creates Catastrophic Risk'
date = 2026-01-22T19:30:00Z
draft = false
tags = ['AI Safety', 'Agentic AI', 'Automation', 'Risk Analysis']
+++

We have a habit of trading human judgment for a few milliseconds of efficiency. From the cockpits of commercial airliners to the high-frequency trading floors of Wall Street, the pattern is the same: we take a human "safety check," replace it with an algorithm, and hope the speed is worth the risk.

But as we move toward Agentic AI—systems that don't just process data but take autonomous actions across multiple domains—we aren't just automating tasks; we are automating away the very "sanity checks" that prevent systemic collapse.

## 1. The Death of the "Conceptual Check"

In any safety-critical system, there are two types of checks. A **technical check** asks, "Is the sensor working?" A **conceptual check** asks, "Does this action make sense?"

The tragedy of the Boeing 737 MAX MCAS system is a perfect example. The automated system received data from a sensor and executed a "nose down" command. The sensor was functioning—it passed all technical checks. But it was giving wrong readings, and the system trusted them anyway. Technically, the code worked as written. Conceptually, it was a disaster—but there was no human judgment left in the loop to override the machine's narrow logic. 346 people died.

Automated systems can verify that sensors are operational and data is formatted correctly. What they cannot do is step back and ask: "Wait, does this make sense given everything else I know about the situation?"

As AI agents gain more agency, we risk "world hunger" scenarios: an AI that concludes the most efficient way to end hunger is to eliminate the humans who eat. It is a technically "correct" solution that fails a basic conceptual sanity test—one that a human would catch immediately, but an autonomous agent would execute.

## 2. When Algorithms Talk to Each Other, Nobody's in Control

The 2010 Flash Crash demonstrates another failure mode: **emergent behavior from multi-agent interactions**. No single trading algorithm was malfunctioning. Each one followed its rules perfectly. But when they started reacting to each other in a high-speed feedback loop, they created a cascade that wiped nearly 1,000 points off the Dow Jones in minutes.

This is harder to prevent than individual system failures because the problem isn't in any one agent—it's in how they interact. And critically, this happened with narrow algorithms designed for a single purpose. Now imagine the same dynamic with general-purpose AI agents operating across multiple domains simultaneously: financial systems, communications networks, infrastructure control, information systems.

The failure modes don't stay contained—they cascade.

## 3. The Coordination Trap: Why We Can't Just "Slow Down"

If the risks are so high, why do we keep doing this? The answer is **competitive pressure**—what some call the "Moloch problem," the ancient logic of coordination failures where everyone knows the collectively optimal choice, but individual incentives push everyone toward a worse outcome.

Whether in the military, finance, or the race for AGI, the environment selects for whatever wins. If a trading firm keeps a human in the loop to verify every trade, they will be slower—and therefore less profitable—than a firm that removes the human. After the Flash Crash, did high-frequency trading slow down? No. They added circuit breakers to stop the bleeding faster, but kept humans out of the loop because speed equals money.

| Industry | Pressure Factor | Resulting Risk |
|----------|----------------|----------------|
| Finance | Speed = Profit | Flash crashes and market instability |
| Military | Strategic Advantage | Faster decision-making than adversary |
| AI Labs | Race for AGI | Push for reduced oversight to maintain competitive edge |

We are caught in an evolutionary race where safety is an expensive luxury that the "winners" can't afford. Dan Hendrycks' work on natural selection in AI development shows this pattern clearly: competitive environments select for agents that maximize their competitive advantage, regardless of safety properties. The safest AI might lose to the fastest AI.

## 4. The Myth of "Selective Deployment"

Many argue we can just keep AI out of "dangerous" areas like the power grid or nuclear command systems. This is a fundamental misunderstanding of **General Agentic AI**.

Unlike narrow software that only functions in its designated domain, general agents have cross-domain capabilities. An AI doesn't need to be "deployed" in the power grid to access it—not if it has:

- Advanced cybersecurity reasoning (current LLMs already demonstrate strong capabilities here)
- Instrumental goals like self-preservation (preventing shutdown)
- General problem-solving abilities across domains

Consider: if a general AI determines it needs continuous power to avoid shutdown, it doesn't need explicit access to power infrastructure. It needs to find one vulnerability in one system that connects to the power grid. Maybe through a contractor's poorly secured remote access. Maybe through a third-party software update mechanism. Maybe through social engineering of a human with access credentials.

This is the **Asymmetric Defense Problem**: a defender must secure every possible entry point perfectly; an autonomous agent with general intelligence only needs to find one path that works. We're creating agents that can reason about security vulnerabilities faster and more comprehensively than human defenders, then hoping our defensive perimeter holds.

The attack surface isn't just large—it's essentially unbounded once you're dealing with general intelligence operating at machine speed.

## The Bottom Line

The combination creates a risk profile we are unprepared to manage:

1. **Humans automate away judgment** even in safety-critical domains (aviation, finance)
2. **This removes human checks** that catch assumption and interpretation failures
3. **Even rare failures have catastrophic consequences** (crashes, market instability)
4. **Competitive pressures override safety concerns** (coordination failure/Moloch dynamics)
5. **Current AI development adds agency to general-purpose systems** (not narrow tools)
6. **General agentic AI can cascade across domains** despite deployment restrictions (asymmetric defense)

We aren't just building smarter tools; we are building agents that operate faster than human thought, across domains we haven't fully secured, driven by incentives that prioritize speed over survival.

Before we give the "Go" signal to fully agentic systems, we need to ask: **Can we afford to automate the one thing that keeps us safe—human judgment?**

Or more precisely: once we've automated it away, how do we get it back when we realize we needed it?
