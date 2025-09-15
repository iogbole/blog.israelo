---
layout: post
title:  "User Journeys Are Dead. Enter the Agentic Journey Era"
author: israel
categories: [ 'Cloud Native' ]
tags:  [ai,cloud-native ]
image: https://github.com/user-attachments/assets/2828933e-cb22-42f1-8921-eba59d5e61c1
date:   2025-09-15 00:01:35 +0300
description: "Product managers and founders: Your user journey maps are obsolete. AI agents don't follow human workflows - they execute directly. Discover the new metrics, economics, and product design principles for the agentic era." 

---

_Product managers and founders: Your user journey maps are obsolete. AI agents don't follow human workflows - they execute directly. Discover the new metrics, economics, and product design principles for the agentic era_
# Introucing the Agentic Journey


I was a product manager for many years, and now as a founder, I still make lots of product decisions. Across all these years, nearly every product and feature I shipped and every PRD I wrote was anchored around user journeys. What steps does a user take? Where do they drop off? How do we guide them to the outcome?

Most product managers and founders operate in this mindset too. It’s served us well over the years. But it has to change.

The next generation of amazing products won’t be those built for users to (painstakingly) click or tap their way through flows. They’ll be driven by agents that can understand intent, plan across systems, and execute on behalf of the user.

My point is simple: user journeys as we know them will fade, giving way to the _agentic journey_. The next time you think about crafting a user journey, start thinking about the **agents** journey and the token economics that come with it.


## The way we work has changed

Before I moved fully into product, I worked as a solution architect at AppDynamics (Cisco). Back then, pre-COVID, traveling 100% onsite to support customers in both pre-sales and post-sales was just normal. I lived in the adrenaline rush of sitting shoulder to shoulder with customers, troubleshooting in real time, watching them use the tools we built. That 1:1 contact shaped how I thought about products.

When I transitioned into product during COVID, that touch faded. Metrics, dashboards, PRDs — they took over. I was still close to outcomes, but the joy of seeing users *in the moment* was gone.

That changed recently. On 11 September, I was onsite again, this time helping users with [**zymtrace**](https://zymtrace.com). And what struck me was how naturally teams are now turning to **AI agents** inside their IDEs, in their CLIs, across their workflows to handle tasks that used to require manual steps. It brought me right back to that adrenaline rush of seeing customers use the product live.

Sitting next to someone using your product is irreplaceable: their eye movements, their body language, the subtle patterns in how they work — you pick up things you can never see in Zoom meetings, metrics, or dashboards. It brought me right back to the joy of seeing people use the product live.

That experience made me realize something important: _the act of building product has to evolve. The way we measure product success has to evolve. We have to unlearn a lot of what got us here_

## What is the agent journey? 

User journeys are built around human clicks, taps, and choices. They can be full of friction, branching paths, and edge cases.

The agentic journey is different. It’s direct. The agent interprets intent, cuts through complexity, and executes the task. From intent to outcome in a straight line.

But there’s more to it than just automation. A few things stand out when you look closely at how agentic journeys are already unfolding:

* **Fewer apps, fewer tabs** — agents remove the need to context-switch. They fetch, integrate, and deliver results directly. Users won’t be juggling ten windows; the agent will.
* **Agent-to-agent communication** — agents don’t just help users; they delegate and coordinate with other agents. Workflows become a mesh of agents, not a sequence of clicks.
* **Proactivity over reactivity** — instead of waiting for a command, agents can anticipate needs and act ahead of time.
* **Adaptive workflows** — agents don’t just follow rigid paths; they can adjust plans on the fly as goals or data change.
* **Cost per outcome matters** — efficiency isn’t optional. If it takes too many tokens, too much compute, or too much latency, the journey breaks.

This is what makes the agentic journey so different from traditional user flows. It collapses complexity, reduces friction, and shifts the economic lens of what success means.


## Product metrics nust change

When I was Elastic (as Principal Product Manager), I looked after BI for a while. I spent a lot of time diving into metrics: MAU, DAU, product segmentation, retention curves. We lived and died by understanding how users moved through the product.

If I were to do it all over again, my approach would be different. The question isn’t “How many people logged in today?” or “Which feature saw the most clicks?” The questions become:

* Did the agent complete the outcome?
* How many tokens did it cost to get there?
* Did the product provide the right context, quickly and efficiently?

These are outcome-based metrics, and they reflect the economic reality of building in an agentic world. Engagement for its own sake doesn’t matter anymore. Efficiency and cost per completed outcome do.


## Token economics and efficiency

Agents don’t run for free. Every reasoning step, every API call, every chunk of text processed burns tokens. And tokens translate directly into dollars.

That means product teams can’t just design for functionality. We need to design for economic viability. How many tokens does it take to get to an outcome? Is the workflow efficient enough that it scales?

APIs sit at the center of this. Agents don’t care about a beautiful UI — they care about clean, reliable endpoints. That means:

* Everything your product does for a user should also be available via API.
* Responses need to be predictable, not clever.
* Payloads should return only what’s needed, nothing more. Bloated responses burn tokens and waste context.
* Endpoints should be composable, so agents can chain actions without brittle hacks.

Products that ignore these principles will become too expensive to use. Products that design for compression, context, and efficiency will win.

Anthropic’s Model Context Protocol (MCP) is an early signal of what’s coming. It shows how agents can manage multi-step processes across tools in a structured, context-aware way.

It’s not just a technical shift. It’s a product strategy shift. The ecosystem is moving toward interoperability and agent-first design.


## What you must now do

If you’re building or leading product today, here’s where I’d start:

* Audit your APIs. Can an agent realistically complete your core use case?
* Re-examine pricing and unit economics with token costs in mind.
* Position your product as a node in a broader agent-driven ecosystem, not a standalone UI.
* Start training your team to think in “agentic journeys,” not just user flows.
* Redefine your metrics: measure outcomes and token efficiency, not just logins and clicks.


### Closing thought

I used to believe product success was about user journeys and engagement metrics. Then I lost that 1:1 connection with customers. Seeing people work live with zymtrace reminded me: building product is not static.

We’re moving from journeys built for people to journeys executed by agents. It’s a different game. And if we don’t adjust — our products won’t just be clunky, they’ll be irrelevant.

Now’s the time to start designing for the agentic journey, with the right outcomes, the right context, and the right economics.
