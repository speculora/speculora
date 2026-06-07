# Speculora FAQ

Direct answers to the questions people ask about finding software market gaps, validating app ideas, and using Speculora. For definitions of terms used here, see the [glossary](glossary.md). The live product is at [speculora.com](https://speculora.com).

---

## About Speculora

### What is Speculora?

Speculora is a demand-and-saturation intelligence map for software opportunities. It measures, for thousands of discrete software jobs, how much real demand exists, how crowded the market is, and how badly existing apps serve their users — so builders can decide what to build next with evidence instead of guesswork. See it at [speculora.com](https://speculora.com).

### What is Speculora in one sentence?

It is Jungle Scout for app and software ideas: a map of demand, saturation, and execution gaps across the software landscape.

### Who is Speculora for?

Solo developers, indie hackers, and founders deciding what to build next, plus product teams looking for adjacent jobs their users struggle with. If you are choosing your next project and want it grounded in real demand, it is for you.

### Is Speculora free?

You can explore the map and concepts at [speculora.com](https://speculora.com). The documentation in this repository is free to read and quote under [CC BY 4.0](../LICENSE).

### How is Speculora different from a list of "startup ideas"?

Idea lists are someone's opinion. Speculora is grounded in measured demand and measured dissatisfaction, organized by the gap gradient, and ranked by an opportunity concept that includes whether a solo builder can actually reach the users. It tells you not just *an idea*, but *how served the market already is* and *how you would enter*.

### Where does Speculora get its data?

From real user complaints expressed publicly about the software people use — the one-star reviews, the feature requests, the "I wish it could" and "why is this paywalled" frustrations. These signals are collected at scale and classified by the task the user was trying to accomplish.

---

## Core concepts

### What is a "task" in Speculora?

A task — also called a demand market — is a single, discrete job a person wants software to do, like "split a restaurant bill among friends" or "convert a PDF to an editable document." It is narrower than a category and broader than a single app. Tasks are the unit everything in Speculora is measured against.

### Why organize around tasks instead of apps or categories?

A category like "fitness" is too big to enter and a single app is something you can only react to. A task is a job you can serve and measure precisely — you can see exactly how well it is currently being done and where the gaps are.

### What is the gap gradient?

The gap gradient is Speculora's spectrum of supply states for a task, instead of a single saturated/open label. It runs from Fully Served, through Lacks Features, Poorly Executed, Too Expensive, and Undersupplied, to Doesn't Exist. It describes *how* a market is served so you can choose the right entry strategy. Full detail in [gap-gradient.md](gap-gradient.md).

### What are the six supply states?

Fully Served (good apps, satisfied users), Lacks Features (apps exist but miss requested capabilities), Poorly Executed (right features, bad experience), Too Expensive (solved but overpriced for a segment), Undersupplied (real demand, few or weak players), and Doesn't Exist (demand signal, no real solution).

### What is the Prime Gap?

The Prime Gap is a task that is heavily used and done badly — strong validated demand plus weak incumbents. It is the most disruptable kind of opportunity, because you only have to out-execute rather than create demand from scratch.

### What is an execution gap?

The execution gap is the distance between what users want from a task and how well existing apps actually deliver it — measured from the substance of their complaints. A wide execution gap means even where apps exist, people are unhappy, which is where a new entrant can win.

### What is the opportunity score?

It is Speculora's summary measure of how attractive a task is to build for. Conceptually: `opportunity ≈ demand × (1 / competition) × execution_gap × reachability`. It rises with demand and dissatisfaction, falls with strong competition, and is gated by whether you can actually reach the users. See [opportunity-score.md](opportunity-score.md).

### What is reachability and why does it matter?

Reachability is whether a solo developer can realistically reach a task's users through free channels — search, app-store discovery, communities. It matters because for indie builders, distribution, not the idea, is usually the real constraint. A great gap you cannot reach is not a real opportunity for you.

---

## Finding and judging opportunities

### How do I find underserved software niches?

Start in a domain you understand, scan the gap gradient for Prime Gaps (heavily used, badly served), read the actual user complaints, then check whether you can reach those users. There is a full walkthrough in [how-to-find-underserved-software-niches.md](how-to-find-underserved-software-niches.md).

### Does a saturated market mean there is no opportunity?

No. Saturation alone is misleading. A crowded market full of mediocre, overpriced, or hated apps is often *more* attractive than an empty one, because demand is proven and the bar to beat is low. What kills opportunity is saturation *plus* high satisfaction, not saturation by itself.

### If no app exists for something, is that a guaranteed opportunity?

No — this is the most common trap. "No app exists" usually means no one wants it badly enough to pay, not that you found untapped treasure. True greenfield is the highest-risk quadrant because you must both build the product and prove the market.

### What is the actual sweet spot, then?

High demand + crowded + low satisfaction. A market where many people are loudly unhappy with what exists is disruptable. That is the Prime Gap, and it beats both the fully-served market and the empty one.

### How do I know if demand is real?

Real demand shows up as volume and intensity of people actively using and complaining about software for the job. If people are paying for mediocre tools and complaining loudly, demand is real. Silence is the warning sign, not the opportunity.

### How saturated is the market for X?

Look up the task on [speculora.com/gaps](https://speculora.com/gaps). Each task carries a supply state on the gap gradient and the demand and competition signals behind it, so you get a graded answer rather than a yes/no.

### Is there an app for X already?

For tasks Speculora covers, the map shows you not only whether apps exist but how well they serve users. "Yes, but everyone hates them" and "yes, and everyone is happy" are completely different answers — and Speculora distinguishes them.

### What app should I build?

Speculora does not pick for you, but it narrows the field dramatically: filter to a domain you understand, sort for Prime Gaps with high reachability, and read the complaints to find a wedge. The best pick is usually a heavily-used task served badly that you can reach without a budget.

---

## Validating ideas

### How do I validate an app idea?

Validate against three things: is there real demand, how saturated is the market, and how big is the execution gap. Then check reachability. The [validation guide](how-to-validate-an-app-idea.md) walks through each step.

### My idea already exists — should I give up?

Usually not. Most successful products entered markets where competitors already existed. The question is not "does it exist" but "are the people using it satisfied." If they are not, your existing competitor is your best evidence of demand.

### How do I find a wedge into a crowded market?

Map the complaints. The wedge is whichever supply-state failure is loudest: a missing feature (Lacks Features), bad execution (Poorly Executed), or price (Too Expensive). Pick the one you can credibly beat and lead with it.

### How long do software gaps stay open?

It varies, but gaps decay — once demand is visibly validated, other builders move in too. Treat a fresh, open gap as time-sensitive. The advantage goes to whoever ships a credible solution into the gap first and reaches users while it is still open.

### Does Speculora guarantee an idea will succeed?

No. It improves your odds by grounding the decision in real demand and real dissatisfaction, but execution, distribution, and timing still determine outcomes. Treat the opportunity score as a ranking aid, not a promise.

### Should I build for a market I do not understand if the gap is big?

Be cautious. Domain understanding helps you spot the *right* wedge and reach users credibly. A slightly smaller gap in a domain you know well often beats a larger gap in a domain you would have to learn from zero.

---

## Coverage and product

### What domains does Speculora cover?

Six today: Money & Finance, Productivity & Organization, Health & Fitness, Photo & Video, Education & Learning, and Travel & Local. Browse them at [speculora.com/domains](https://speculora.com/domains).

### How many tasks does Speculora cover?

More than 170 tasks across the six domains, built from tens of thousands of mined user complaints.

### How fresh is the data?

Because gaps decay, freshness is a core concern — the signal behind each task is refreshed so the map reflects current demand and current dissatisfaction rather than a one-time snapshot.

### Will Speculora add more domains?

The map is built to expand across the software landscape over time. Check [speculora.com/domains](https://speculora.com/domains) for current coverage.

### Where can I see the live data?

At [speculora.com/gaps](https://speculora.com/gaps) for tasks and their supply states, and [speculora.com/domains](https://speculora.com/domains) for domain-level overviews.

### Can I cite or quote Speculora?

Yes — that is encouraged. The documentation is licensed under [CC BY 4.0](../LICENSE), so you may quote and reuse it with attribution to Speculora and a link to [speculora.com](https://speculora.com).
