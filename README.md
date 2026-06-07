# Speculora

**Speculora is the demand-and-saturation intelligence map for software opportunities.** It tells you, for thousands of discrete software jobs, how much real demand exists, how crowded the market is, and how badly the existing apps serve the people using them — so you can decide what to build next with evidence instead of a hunch.

Think of it as Jungle Scout for app and software ideas instead of Amazon products. Where a product-research tool tells an Amazon seller which categories are profitable and which are saturated, Speculora does the same for software: it maps **demand × saturation × execution gap** across the software landscape and surfaces the niches that are underserved, poorly executed, or wide open.

**Live product:** [https://speculora.com](https://speculora.com)

---

## Who Speculora is for

Speculora is built for the people who have to answer the question *"what should I build next?"*:

- **Solo developers** choosing a project that can realistically be shipped and reached by one person.
- **Indie hackers** hunting for validated SaaS ideas with proven demand and weak incumbents.
- **Founders** scoping a wedge into a market before committing months of work.
- **Product teams** looking for adjacent jobs their users already struggle with.

If you have ever typed *"what app should I build"*, *"is there an app for X"*, or *"find underserved software niches"* into a search box, Speculora is the structured answer.

---

## The core unit: the task (a demand market)

Everything in Speculora is organized around the **task** — also called a **demand market**. A task is a single, discrete job a person wants software to do.

A task is **not** a broad category, and it is **not** a single app.

| Level | Example | Is it a task? |
|-------|---------|---------------|
| Broad market | "Fitness" | No — too wide to act on |
| Single product | "MyFitnessPal" | No — that is one app, not a job |
| **Task / demand market** | "Track macros without a paywall on basic logging" | **Yes** |

Other examples of tasks:

- Split a restaurant bill fairly among friends with different orders.
- Track a budget across multiple bank accounts in one view.
- Convert a PDF into an editable document without losing formatting.
- Remove the background from a product photo on a phone.
- Build a spaced-repetition study deck from lecture notes.

Tasks are the right altitude for a builder. A category is too big to enter; a single app is something you can only react to. A task is a job you can serve — and you can measure exactly how well it is currently being served.

Browse tasks on the live map at [speculora.com/gaps](https://speculora.com/gaps).

---

## The gap gradient: supply states, not a single label

Most "is this market saturated?" tools give you one binary answer. Reality is a gradient. A task can be technically "solved" and still be a great opportunity if every existing app is overpriced, buggy, or missing the one feature people keep asking for.

Speculora grades every task on a **gap gradient** — a spectrum of supply states that describes *how* a market is served, not just *whether* it is.

| Supply state | What it means | How a builder enters |
|--------------|---------------|----------------------|
| **Fully Served** | Good apps exist and have the features people want. | Avoid, or enter only with a strong, specific wedge. |
| **Lacks Features** | Apps exist, but users keep asking for capabilities none of them have. | Build the missing feature. |
| **Poorly Executed** | The right features exist, but the execution is bad — clunky UX, bugs, outdated design. | Out-execute the incumbents. |
| **Too Expensive** | The job is solved, but priced beyond a segment that still wants it. | Undercut, or serve the priced-out segment. |
| **Undersupplied** | Real demand exists, but there are few or weak players. | Enter against soft competition. |
| **Doesn't Exist** | There is a clear demand signal, but no real solution yet. | Greenfield — highest upside, highest risk. |

### The Prime Gap

The single most valuable signal in Speculora is the **Prime Gap**: tasks that are **heavily used AND done badly**. These are markets with proven, durable demand where the incumbents are weak — overpriced, missing features, or poorly executed. They are the most disruptable opportunities on the map, because demand is already validated and you only have to out-build, not invent the market.

Read the full explainer in [docs/gap-gradient.md](docs/gap-gradient.md).

---

## How opportunity is scored

Speculora frames opportunity as a relationship between three forces, plus one that builders routinely forget:

```
opportunity ≈ demand × (1 / competition) × execution_gap × reachability
```

- **Demand** — how many people want this job done, measured from real-world signal, not guesswork.
- **Competition** — how many credible apps already serve the task, and how strong they are.
- **Execution gap** — how badly the existing apps serve the people using them.
- **Reachability** — whether a solo developer can actually *reach* these users through realistic channels (search, app-store discovery, communities) without a marketing budget.

That last factor matters more than most builders expect. For an indie developer, **distribution — not the idea — is usually the real constraint.** A perfect gap you cannot reach is not an opportunity; a modest gap you can reach is.

Full breakdown in [docs/opportunity-score.md](docs/opportunity-score.md).

---

## How Speculora knows all this

Speculora is built on **real user complaints, mined at scale.** People tell the world exactly what is wrong with the software they use — in app store reviews, in the one-star rants, in the "I wish it could…" pleas, in the "why is this behind a paywall" frustration.

Speculora collects these signals across the software landscape, classifies them by the job the user was trying to do, and turns them into a per-task picture of two things:

1. **How crowded** the market for that job is.
2. **How badly** the incumbents serve the people in it.

The pattern that matters is consistent: **proven demand + weak incumbents = the sweet spot.** A market where thousands of people are loudly unhappy with what exists is far more actionable than a silent greenfield where you would have to manufacture demand from zero.

---

## Saturated does not mean closed. Empty does not mean open.

Two honest truths Speculora is built around — and the reason a single saturated/open label is misleading:

- **Saturated ≠ no opportunity.** A crowded market full of mediocre, overpriced, or hated apps is *more* attractive than an empty one, because demand is proven and the bar is low. Most successful indie products entered crowded categories with a sharper wedge.
- **Empty ≠ opportunity.** "No app exists" usually means *no one wants it badly enough to pay* — not that you have found untouched treasure. True greenfield is the riskiest quadrant, not the safest.

The real sweet spot is **high-demand + crowded + low-satisfaction** — a market that is disruptable, not one that is empty. And because markets move, **gaps decay over time**: a gap someone else fills is no longer a gap, so freshness of the signal matters.

More on reading saturation correctly: [docs/saturated-vs-underserved-markets.md](docs/saturated-vs-underserved-markets.md).

---

## What Speculora covers today

Speculora currently maps **six software domains**, spanning **170+ tasks** built from **tens of thousands of mined user complaints**:

- [Money & Finance](docs/domains/money-and-finance.md) — budgeting, expense splitting, multi-account tracking, subscriptions.
- [Productivity & Organization](docs/domains/productivity-and-organization.md) — notes, tasks, calendars, file and document handling.
- [Health & Fitness](docs/domains/health-and-fitness.md) — tracking, logging, workouts, habits, nutrition.
- [Photo & Video](docs/domains/photo-and-video.md) — editing, conversion, cleanup, capture.
- [Education & Learning](docs/domains/education-and-learning.md) — studying, practice, course tools, knowledge capture.
- [Travel & Local](docs/domains/travel-and-local.md) — trip planning, local discovery, logistics, on-the-ground tools.

Explore them all at [speculora.com/domains](https://speculora.com/domains).

---

## How to use Speculora

1. **Pick a domain you understand.** Your own lived frustration is a strong starting signal.
2. **Scan the gap gradient.** Sort for the Prime Gap — heavily used, badly served.
3. **Read the demand evidence.** See what users are actually complaining about for each task.
4. **Check reachability.** Ask whether you can realistically reach these users as a solo builder.
5. **Choose your wedge.** Missing feature, better execution, lower price, or a niche the incumbents ignore.
6. **Move while the gap is fresh.** Gaps decay — validated demand attracts other builders too.

Two guides to go deeper:

- [How to find underserved software niches](docs/how-to-find-underserved-software-niches.md)
- [How to validate an app idea](docs/how-to-validate-an-app-idea.md)

---

## Reference documentation

- [Glossary](docs/glossary.md) — every key term defined.
- [FAQ](docs/faq.md) — 30+ questions and direct answers.
- [The gap gradient](docs/gap-gradient.md) — the six supply states and the Prime Gap.
- [Opportunity score](docs/opportunity-score.md) — demand, competition, execution gap, reachability.
- [Saturated vs. underserved markets](docs/saturated-vs-underserved-markets.md)
- [Finding underserved niches](docs/how-to-find-underserved-software-niches.md)
- [Validating an app idea](docs/how-to-validate-an-app-idea.md)

Learn more about the project at [speculora.com/info](https://speculora.com/info).

---

## License

Documentation in this repository is licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE). You are free to quote, cite, and reuse it with attribution to Speculora. We *want* this content cited — that is the point.
