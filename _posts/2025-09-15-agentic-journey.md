---
layout: post
title:  "User Journeys Are Dead. Enter the Agentic Journey Era"
author: israel
categories: [ 'Cloud Native' ]
tags:  [ai,cloud-native ]
image: https://github.com/user-attachments/assets/2828933e-cb22-42f1-8921-eba59d5e61c1
date:   2025-09-30 06:01:35 +0300
description: "AI agents don’t follow human workflows — they execute directly. Here’s how metrics, economics, and product design must evolve for the agentic era" 
---

For years, product managers and founders (myself included) built products around user journeys. We mapped every click, tap, and drop-off point. We obsessed over funnels, session duration, flows, DAU (Daily Active Users), MAU (Monthly Active Users).

That era is ending. The PRD structure must evolve.  

The next generation of **amazing products** won’t be defined by users (painstakingly) clicking or tapping through flows. They’ll be powered by **AI agentic systems** that understand intent, plan across platforms, and execute on behalf of the user.

The [BLUF](https://israelo.io/blog/bluf/) is:  user journeys as we know them are fading, giving way to the **agentic journey**. When designing for product, you must now consider **AI agents** and how they achieve outcomes. Go further by factoring in **token economics** and create **AI eval frameworks** for measuring success. Traditional metrics like clicks, session duration and active sessions are headed for obsolescence, just like the journeys themselves.

The future belongs to products that orchestrate outcomes, not just user interactions.

# Why This Hit Me

Early in my career at AppDynamics (Cisco), I spent nearly all my time onsite with customers, supporting both pre-sales and post-sales activities (depending on the quarter). Sitting shoulder to shoulder, I could see every hesitation, every workaround, every aha moment. That intimacy shaped how I thought about product.


During COVID, when I moved into product management full-time, that contact disappeared. PRDs, metrics, and dashboards replaced real-time user insight. FWIW, user interviews are never the same as watching users interact with your product—their body language, the subtle patterns in how they work—you notice things you can never capture in Zoom meetings, metrics, or dashboards.

Recently, onsite with a [**zymtrace**](https://zymtrace.com) customer, I felt that old rush again. What struck me wasn’t just how people used the product, but how naturally they leaned on **AI agents** in their IDEs, CLIs, and workflows. Tasks that once required manual steps were now offloaded to agents. It drove home a truth: **the way we build and measure products has to evolve.**

The contrast between these experiences—then and now—makes one thing absolutely clear: product design is no longer just about user interaction; it must now include considerations on how AI agents can achieve the intended outcome. We must rethink product success metrics.

## What Really Is the Agentic Journey?

**Agentic journeys** are fundamentally different from traditional user flows. Unlike conventional journeys, they don’t require users to follow predefined paths—they understand the user’s goals from the outset. Agents interpret intent, navigate complexity, and execute tasks on behalf of the user, turning multi-step workflows into seamless outcomes.

When I say **agent** here, I mean an AI system that, once given a goal, autonomously chooses its next step—selecting and invoking tools, planning or revising its approach, and using real-world feedback (API responses, errors, intermediate state) to iteratively reach an outcome instead of executing a fixed, hardcoded sequence [ref: Anthropic: Building effective agents](https://www.anthropic.com/engineering/building-effective-agents)

Key characteristics of agentic journeys include:

* **Fewer apps, fewer tabs** — Agents eliminate context-switching by fetching, integrating, and delivering results directly. Users no longer juggle multiple windows; the agent handles it.

* **Agent-to-agent communication** — Agents coordinate with one another to delegate tasks and orchestrate workflows. Workflows become a collaborative mesh of agents, not a linear sequence of clicks.


* **Adaptive workflows** — Agents adjust plans in real-time as goals or data change, rather than following rigid, predefined paths.

* **Cost per outcome matters** — Efficiency is critical. Excessive compute, tokens, or latency can break the journey.


For example, the [**Agent2Agent (A2A) Protocol**](https://developers.googleblog.com/en/a2a-a-new-era-of-agent-interoperability), introduced by Google in April 2025, enables secure communication and collaboration between AI agents across different platforms and vendors. It allows them to share context and coordinate actions seamlessly. Additionally, the [**Agent Payments Protocol (AP2)**](https://cloud.google.com/blog/products/ai-machine-learning/announcing-agents-to-payments-ap2-protocol), announced in September 2025, provides a standardized framework for secure, compliant transactions conducted by AI agents on behalf of users.

These protocols illustrate how agentic AI systems are evolving to manage complexity, collaborate autonomously, and perform transactions securely. 

## Product Metrics Must Change Too

When I was at Elastic (as Principal Product Manager), I managed BI for a while. I spent a lot of time diving into metrics: MAU, DAU, product segmentation, retention curves. We lived and died by understanding how users moved through the product.

If I were to do it all over again, my approach would be different. The questions aren’t “How many people logged in today?” or “Which feature saw the most clicks?” Instead, they become:

* Did the **agent** complete the intended outcome?
* How many **tokens** did it cost to get there?
* Did the product provide the **right context**, quickly and efficiently?

These are **outcome-based metrics**—they reflect the economic reality of building in an agentic world. Engagement for its own sake doesn’t matter anymore. What matters is **efficiency** and **cost per completed outcome**.

To make these metrics actionable, I’d build evals to measure success: automated tests, benchmarks, and simulations that validate whether agents achieve outcomes reliably, efficiently, and safely. This shifts the focus from counting clicks or logins to understanding real impact.

Here’s a tightened rewrite of that section, with the Gartner citation explicitly tied back to **why token economics matters**:

## Token Economics and Efficiency

Agents don’t run for free. Every reasoning step, API call, and chunk of text processed burns tokens—and tokens translate directly into dollars.

That means product teams can’t just design for functionality. We need to design for **economic viability**. How many tokens does it take to reach an outcome? Is the workflow efficient enough to scale?

APIs sit at the center of this. Agents don’t care about a beautiful UI—they care about clean, reliable endpoints. That means:

* **Expose everything via API** — Every product feature available to a user should also be accessible programmatically.
* **Predictable responses** — Agents need consistency, not cleverness.
* **Minimal payloads** — Return only what’s necessary. Bloated responses waste tokens and context.
* **Composable endpoints** — Agents should be able to chain actions without brittle hacks.

Products that ignore these principles will quickly become too expensive to use. Products that design for **compression, context, and efficiency** will win.

Gartner’s research underscores this point: more than 40% of agentic AI projects are expected to be scrapped by 2027 because costs spiral out of control and business value remains unclear ([Reuters](https://www.reuters.com/business/over-40-agentic-ai-projects-will-be-scrapped-by-2027-gartner-says-2025-06-25)). In other words, ignoring token economics isn’t just inefficient—it can be fatal to the viability of entire product lines.


Anthropic’s **Model Context Protocol (MCP)** is an early signal of what’s coming. It shows how agents can manage multi-step processes across tools in a structured, context-aware way.

This isn’t just a technical shift—it’s a **product strategy shift**. The ecosystem is moving toward **interoperability** and **agent-first design**, where efficiency and cost per outcome drive product decisions.


## What You Must Now Do

If you’re building or leading product today, here’s where I’d start:

* **Audit your APIs** — Can an agent realistically complete your core use case?
* **Re-examine pricing and unit economics** — Factor in token costs and operational efficiency.
* **Position your product as part of an agent-driven ecosystem** — Don’t treat it as a standalone UI.
* **Train your team to think in “agentic journeys”** — Go beyond traditional user flows.
* **Redefine your metrics** — Measure outcomes and token efficiency, not just logins and clicks.

## Closing Thought

Watching customers use [**zymtrace**](https://zymtrace.com) in real time reminded me that building product is never static.

We must shift, albeit gradually, from product journeys designed for people to journeys carried out by AI agents. It’s a new model, and if we don’t adapt, our products won’t just feel clunky; they’ll risk becoming irrelevant.

The next time you discuss product user journeys with your peers or team, ask: *What does the agentic journey look like, and how do we build evals to measure its success?*
