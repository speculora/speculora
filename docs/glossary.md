# Speculora glossary

Clean definitions of every key term used across Speculora. For the bigger picture, start with the [README](../README.md), and explore the live map at [speculora.com](https://speculora.com).

---

## Task (demand market)

A **task** — also called a **demand market** — is a single, discrete job a person wants software to do, stated at the level a builder can actually serve. "Split a restaurant bill among friends," "convert a PDF to an editable document," and "track a budget across multiple bank accounts" are tasks. A task sits between a broad market (too wide: "finance") and a single product (too narrow: one named app). It is the atomic unit of Speculora: every measurement of demand, saturation, and gap is computed per task.

## Demand

**Demand** is how many people want a given task done, and how strongly. In Speculora, demand is inferred from real-world signal — the volume and intensity of people actively using and complaining about software for that job — rather than from surveys or speculation. High demand means the market is real and already paying attention.

## Saturation

**Saturation** is how crowded the supply side of a task is: how many credible apps already serve it and how strong they are. Saturation is one input to opportunity, but it is not destiny. A saturated market full of weak, hated, or overpriced apps can be more attractive than an empty one, because demand is proven and the bar to beat is low.

## Competition

**Competition** is the strength-weighted count of existing solutions for a task. It differs from raw saturation in that it accounts for *quality*: ten abandoned, one-star apps represent far less real competition than two beloved, well-funded ones. Speculora treats competition as the denominator of opportunity — more credible competition lowers the score, weaker competition raises it.

## Execution gap

The **execution gap** is the distance between what users want from a task and how well the existing apps actually deliver it. It is measured from the substance of user complaints: missing features, bugs, bad UX, aggressive paywalls, outdated design. A large execution gap means even where apps exist, people are unhappy — which is exactly where a new builder can win.

## Gap gradient

The **gap gradient** is Speculora's spectrum of supply states for a task, replacing the misleading binary of "saturated" vs "open." It runs from *Fully Served* through *Lacks Features*, *Poorly Executed*, *Too Expensive*, and *Undersupplied*, to *Doesn't Exist*. The gradient describes *how* a market is served, not merely *whether* it is, so a builder can pick the right entry strategy. See the [gap gradient explainer](gap-gradient.md).

## Fully Served

A supply state on the gap gradient. **Fully Served** means good apps already exist and have the features people want, with broadly satisfied users. These tasks are the least attractive for a new entrant — you would need a strong, specific wedge to justify competing.

## Lacks Features

A supply state on the gap gradient. **Lacks Features** means apps for the task exist, but users repeatedly ask for capabilities none of the incumbents provide. The entry strategy is straightforward: build the missing feature that people are already requesting.

## Poorly Executed

A supply state on the gap gradient. **Poorly Executed** means the right features exist somewhere, but the execution is bad — clunky interfaces, frequent bugs, slow performance, or dated design. The entry strategy is to out-execute: same job, dramatically better experience.

## Too Expensive

A supply state on the gap gradient. **Too Expensive** means the task is genuinely solved, but the available solutions are priced beyond a segment of people who still want the job done. The entry strategy is to undercut on price or serve the priced-out segment with a leaner offering.

## Undersupplied

A supply state on the gap gradient. **Undersupplied** means real demand exists but there are few players, or only weak ones. Competition is soft, so a competent entrant can capture share without needing a dramatic differentiator.

## Doesn't Exist

A supply state on the gap gradient. **Doesn't Exist** means there is a demand signal but no real solution yet — true greenfield. It carries the highest upside and the highest risk, because you must both build the product and prove the market is willing to adopt and pay.

## Prime Gap

The **Prime Gap** is Speculora's highest-value signal: a task that is **heavily used and done badly**. It combines strong, validated demand with weak incumbents (overpriced, missing features, or poorly executed). Prime Gaps are the most disruptable opportunities on the map because the market is proven — the builder only has to out-execute, not invent demand.

## Opportunity score

The **opportunity score** is Speculora's summary measure of how attractive a task is to build for. Conceptually, opportunity rises with demand and execution gap, falls with competition, and is gated by reachability: `opportunity ≈ demand × (1 / competition) × execution_gap × reachability`. It is a ranking aid, not a guarantee — it points you at the tasks worth investigating closely.

## Reachability

**Reachability** is whether a solo developer can realistically reach the users of a task through channels available without a marketing budget — search, app-store discovery, and relevant communities. A gap you cannot reach is not an opportunity for an indie builder. Reachability is the factor most idea lists ignore and the one that most often decides whether a solo product succeeds.

## Distribution

**Distribution** is how a product gets in front of the people who need it. Speculora treats distribution — not the idea itself — as the usual binding constraint for solo developers. Two products serving the same gap can have wildly different outcomes purely because one is discoverable and the other is not.

## Domain

A **domain** is a top-level grouping of related tasks, used to organize the map. Speculora currently covers six domains: Money & Finance, Productivity & Organization, Health & Fitness, Photo & Video, Education & Learning, and Travel & Local. Browse them at [speculora.com/domains](https://speculora.com/domains).

## Gap decay

**Gap decay** is the tendency of opportunities to shrink over time as other builders notice the same validated demand and enter. A gap that exists today may be filled tomorrow, which is why freshness of the underlying signal matters and why acting while a gap is open is part of the strategy.

## User complaint signal

The **user complaint signal** is the raw material Speculora is built from: real expressions of frustration, unmet need, and feature requests that people leave in public about the software they use. Aggregated and classified by task, this signal is what reveals both how much demand exists and how badly that demand is currently being met.
