---

date: 2026-06-24
author: Mark Williams
summary: Using Radical Product thinking and Theory of Change as a way to articulate the mechanism of change and guardails to enable change
tags:
  - product-management
---


Recently, there's been talk in my organisation of shaping a new function to own an end-to-end user journey that is currently spread across multiple teams. It's broadly considered a good option. The problem is clear enough; a slow, fragmented oexperience that's kind of designed around multiple policies owned by different teams. So users essentially have to navigate the internal org chart as they move through the product. They have to deal with four or five different teams, each owning a different slice, with no single person responsible for how the slices connect.

The experience works, but it can't scale and in that situation, retention is a predictable casualty. First impressions are poor, time to value is long, and a lot of effort on both sides gets spent managing handoffs rather than doing useful work.

The instinct is to propose a pod/team to join it up. I'm in agreement that an otucome focused team could do more than individual support and product teams, but also cautious that we should have some measure of knowing if in 6-12 months that what we proposed is better than what we had. 

Rather than jump straight to structure, I thought I'd try a couple of ways of articulating the "why".

## Radical product vision

If you are trying to align multiple teams around a complex problem, a snappy, single-line vision statement (think: "We want to be the world's most trusted platform for X") usually isn't very useful. It is often too vague to help anyone make a hard trade-off and it missed the context of the actual friction your users are feeling today. I really like using this specific vision framing from [Radical Product Thinking](https://www.radicalproduct.com/). Instead of a glossy tagline, it forces you to articulate a clear narrative: exactly what is broken today, why it is unacceptable, what the ideal future looks like, and the concrete strategy you will use to get there. It gives teams a shared, realistic diagnosis of the problem, which makes deciding what not to build a whole lot easier.

For our new team, I tried something like this:

**Today when…** A user wants to interact with or integrate with our system, they don’t navigate a single platform; they navigate our internal org chart. By forcing users to interact with multiple siloed teams, we optimise for internal boundaries rather than the end-to-end user experience. There is no single owner of the full journey.

**This is unacceptable because…** It creates friction, handoffs, and blind spots. This fragmentation introduces multiple bottlenecks, complicating and delaying the user's journey while placing an unnecessary operational burden on both the users and our internal teams. Ultimately, it slows down the value we are trying to deliver.

**We envision a world where…** Our system is a completely frictionless, self-service platform. A user can onboard, operate, and safely get value autonomously as a seamless process. They view our organisation as a single, cohesive product rather than a collection of distinct teams, without needing manual handoffs or constant internal support.

**We will bring this about by…**

* **Shifting from siloed ownership** to owning the end-to-end user lifecycle as a single product.


* **Treating operational and integration structures as scalable products**, not manual, bespoke processes.


* **Coordinating delivery** so every release includes updated documentation, briefed support, and live readiness from day one.


## Theory of Change

I also wondered if now that we have our vision, a **Theory of Change (ToC)** might give us a lens on how we measure what we think will happen if we do what we propose.

### What actually is a Theory of Change?

Theory of Change is something traditionally used in the charity sector. The basic idea is simple: make the causal chain explicit. If we do X, it enables Y, which produces Z.

The version I outline here shows this journey. It forces you to map out your actions, the internal shifts those actions enable, the user experience that creates, and the wider strategic impact that follows.

When you strip out our specific project details, it looks something like this:

| If we... <br>

<br>**(Our Actions)** | Then teams can... <br>

<br>**(Internal Shifts)** | Which means users... <br>

<br>**(The User Experience)** | Enabling the org to... <br>

<br>**(Strategic Impact)** |
| --- | --- | --- | --- |
| **Shift from siloed ownership to owning the end-to-end journey** as a single product.

 | Baseline and measure the full journey consistently, identifying the highest-value areas for automation.

 | Experience a coherent, predictable service at every stage, without needing to know our internal org chart.

 | Demonstrate platform and business value through robust user satisfaction data.

 |
| **Treat operational structures as scalable products**, not manual processes.

 | Automate high-volume, low-complexity journeys and focus human effort only on complex edge cases.

 | Self-serve routine tasks instantly, without needing to raise support tickets or wait for manual handoffs.

 | Scale the volume of users exponentially without requiring a proportional growth in staff.

 |
| **Coordinate delivery** so every release includes updated docs, briefed support, and live readiness.

 | Spend less time handling avoidable friction and firefighting repetitive queries.

 | Spend less time navigating support and more time successfully getting value from the product.

 | Onboard users faster and at a massive scale, accelerating overall organisational growth.

 |

Writing this out forces you to name the *actual mechanism of change*. Not just asserting "this team will fix fragmented experience," but mapping out specifically how, and what has to change internally before users see any difference.

### The bits that usually break

That middle column — **the internal shifts** — is where proposals tend to fall apart. None of those shifts are guaranteed just by forming a new team. If those shifts don't happen, the causal chain breaks, regardless of what the new team is called.

It also surfaces what I think of as **guardrails** ie. the conditions that *have* to hold for the theory to actually function:

* **Shared Metrics:** Success cannot be measured by individual team throughput; it must be measured by something like total **time-to-value** for the user. If metrics don't change, the incentives don't change, even if the org chart does.


* **Cross-Functional Autonomy:** Teams need the mandate to eliminate friction points that sit on the boundaries between traditional siloes.


* **Product-First Mindset:** Support teams must feed insights directly back into product so recurring queries are treated as bugs to be automated away, rather than just absorbed as an ongoing operational cost.



### How to test the theory before committing

The best thing about this exercise is that it pushes you toward designing a validation point before committing to a full restructure. Rather than reorganising and hoping for the best, you can use a bounded, already-planned piece of work as a test.

If you want to try this out on your own product, you can frame a quick hypothesis like this:

> **The Test:** "If our existing teams work as a joined-up unit on *[Insert an upcoming, well-scoped feature]*, can we ship it to a deadline **AND** ensure documentation is updated, support teams are briefed, and live service is ready from day one?"
> 
> 

If the answer is yes, you have evidence that a joined-up structure works. If the answer is no, it tells you something incredibly important about where the real operational blockers are before you waste time and energy shifting people around on an org chart.

It is treating organisational design a bit like a product problem: form a hypothesis, run the smallest useful test, and learn before you commit.

The framework won't tell you whether your theory is correct, or whether the people with the power to change things will actually change them. But as a way of structuring a proposal and forcing yourself to articulate the actual mechanism rather than just asserting the outcome I think it does a decent job.