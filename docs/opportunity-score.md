# The opportunity score

The opportunity score is Speculora's summary measure of how attractive a software task is to build for. It compresses four forces — demand, competition, execution gap, and reachability — into a single ranking that points you at the tasks worth investigating closely.

It is a compass, not a verdict. A high score says "look here first," not "you will succeed." This page explains what each factor means, why the formula is shaped the way it is, and how to use the score without being misled by it. For the supply-state side of the picture, read [the gap gradient](gap-gradient.md).

---

## The conceptual formula

```
opportunity ≈ demand × (1 / competition) × execution_gap × reachability
```

In plain language: opportunity **rises** with how many people want the job done and how badly it is currently done, **falls** as credible competition increases, and is **gated** by whether a solo builder can actually reach the users.

Each factor is necessary. Set any one of them to near zero and the whole product collapses — which is exactly the point. A huge demand market with happy incumbents (no execution gap) is not an opportunity. A wide-open gap you cannot reach is not an opportunity. The formula encodes that intuition.

---

## The four factors

### Demand

**What it measures:** how many people want this task done, and how strongly.

Demand is the foundation. Without it, nothing else matters — the cleanest execution of a job no one wants is still worthless. Speculora infers demand from real-world signal: the volume and intensity of people actually using and complaining about software for the job, rather than from surveys or intuition. The advantage of complaint-derived demand is that it is *revealed* demand — people only complain about things they actually do.

**Watch for:** confusing your own enthusiasm for market demand. The score is built on what the market signals, not on how exciting the idea feels.

### Competition

**What it measures:** how many credible apps already serve the task, and how strong they are.

Competition is the denominator — more of it lowers opportunity. But Speculora weights competition by *strength*, not just count. Ten abandoned one-star apps are weaker competition than two beloved, well-funded ones. This is why a "crowded" market can still score well: if the crowd is weak, the effective competition is low.

**Watch for:** counting logos instead of reading satisfaction. A long list of competitors that users hate is soft competition, not hard.

### Execution gap

**What it measures:** how badly the existing apps serve the people using them.

This is the factor that turns saturated markets into opportunities. The execution gap is read from the substance of complaints — missing features, bugs, bad UX, aggressive paywalls, outdated design. A large execution gap means even where apps exist, users are unhappy and ready to switch. It is the multiplier that elevates *Lacks Features*, *Poorly Executed*, and *Too Expensive* tasks above merely empty ones.

**Watch for:** assuming a gap you can see is a gap you can close. Some gaps persist because they are genuinely hard; confirm the missing thing is something you can actually build.

### Reachability

**What it measures:** whether a solo developer can realistically reach the task's users through channels available without a marketing budget — search, app-store discovery, and relevant communities.

Reachability is the factor most idea lists ignore and the one that most often decides whether a solo product survives. **For an indie builder, distribution — not the idea — is usually the real constraint.** A perfect gap in a market you can only reach by outspending incumbents on ads is not an opportunity for you. A modest gap whose users actively search for a solution, congregate in findable communities, or browse app-store categories is far more buildable.

**Watch for:** treating reachability as someone else's problem to solve after launch. It should shape which gap you pick in the first place.

---

## Why it is multiplicative, not additive

The factors multiply rather than add because they gate one another. With addition, a sky-high demand score could mask zero reachability and still look attractive. Multiplication enforces the real-world truth that a near-zero in any single factor sinks the whole opportunity — you genuinely need *all four* to line up. This is what keeps the score honest about the difference between an exciting idea and a buildable one.

---

## How to use the score

1. **Rank, then read.** Use the score to sort tasks, then read the underlying demand and complaint evidence for the top candidates. Never act on the number alone.
2. **Sort toward the Prime Gap.** The highest, most actionable scores tend to come from heavily-used tasks with a wide execution gap — the [Prime Gap](gap-gradient.md#the-prime-gap).
3. **Weight reachability for your situation.** A team with a distribution channel can chase gaps a solo developer should skip. Re-weight reachability against your own reality.
4. **Respect gap decay.** A high score is a snapshot. Validated opportunities attract other builders, so a strong score is also a clock — act while the gap is fresh.
5. **Cross-check with domain fit.** A slightly lower-scoring task in a domain you deeply understand often beats a higher-scoring one you would have to learn cold, because understanding sharpens both your wedge and your reach.

---

## What the score does not tell you

- Whether *you specifically* can execute well — that depends on your skills.
- Whether the market will still be open by the time you ship — gaps decay.
- Whether a business model exists — demand to *use* is not always demand to *pay*.
- Whether timing is right — some greenfield gaps are empty because the market is not ready yet.

Treat the opportunity score as the start of due diligence, not the end of it. Combine it with the [gap gradient](gap-gradient.md), the [validation guide](how-to-validate-an-app-idea.md), and your own domain judgment, and explore the live rankings at [speculora.com/gaps](https://speculora.com/gaps).
