<div align="center">

# JioHotstar Discovery
### Find your next watch—with less scrolling.

An independent product-design case study exploring faster, more confident streaming discovery through transparent match scores and mood-led recommendations.

![Portfolio case study](https://img.shields.io/badge/Portfolio-Product%20Design-7c3aed)
![Platforms](https://img.shields.io/badge/Concept-Mobile%20%2B%20Web-0ea5e9)
![Status](https://img.shields.io/badge/Status-Prototype-10b981)

<br />

<img src="project%20images/JioHotstar%20Algorithmic%20UI%20Demo.png" alt="Concept illustration of personalized match scores and mood hubs across TV and mobile" width="100%" />

<br />

[Explore the prototypes](#explore-the-prototypes) · [See the case study](#the-challenge) · [Read the product context](./context.md) · [View the plan](./plan.md)

</div>

> **Independent portfolio concept.** This project is not affiliated with or endorsed by JioHotstar. Product names, logos, and title references belong to their respective owners. Screens, scores, and metrics are illustrative concepts—not production results.

## At a glance

| Challenge | Design direction | Primary success measure |
|---|---|---|
| Viewers can spend too long choosing what to watch. | Make relevance visible and explainable, with optional mood shortcuts. | Session-to-play conversion |

**Role:** Product thinking and interface concept · **Surfaces:** Mobile and web · **Source:** Product requirements document and portfolio prototypes

## The challenge

The supplied PRD describes subscribers spending around **15 minutes browsing** and sessions that end without a video being played. The working hypothesis is that choice overload and low confidence make it harder to find a relevant title.

These are claims from the supplied brief, not independently verified research findings.

## The concept

- **See relevance at a glance:** Show a match percentage on the title card without an extra step.
- **Understand the recommendation:** Offer a concise explanation of the signals behind the match.
- **Narrow by mood:** Use optional mood-led collections as shortcuts into the catalog.
- **Keep discovery familiar:** Enhance the existing experience rather than redesigning the whole home screen.

The concept prioritizes match quality and transparency. A short-form, swipeable trailer feed is intentionally out of scope, consistent with the PRD's non-goals.

## Explore the prototypes

| Mobile concept | Web concept |
|---|---|
| [Open mobile HTML](./prototype/mobile%20screen/code.html) · [Design notes](./prototype/mobile%20screen/DESIGN.md) | [Open web HTML](./prototype/web%20screen/code.html) · [Design notes](./prototype/web%20screen/DESIGN.md) |
| [![Mobile discovery screen](prototype/mobile%20screen/screen.png)](./prototype/mobile%20screen/code.html) | [![Web discovery screen](prototype/web%20screen/screen.png)](./prototype/web%20screen/code.html) |

Open the HTML files in a modern browser to explore the concepts. The prototypes use external font and styling resources, which may require an internet connection. They are static front-end demonstrations and are not connected to a recommendation model or streaming service.

## Case-study visuals

<details>
<summary><strong>01 · The problem — decision fatigue</strong></summary>
<br />

![Decision fatigue in the streaming lounge](project%20images/Decision%20Fatigue%20in%20the%20Streaming%20Lounge.png)

</details>

<details>
<summary><strong>02 · The strategy — goals and success measures</strong></summary>
<br />

![Strategy goals and success metrics dashboard](project%20images/JioHotstar%20Strategy%20Goals%20Dashboard.png)

</details>

<details>
<summary><strong>03 · The solution — match scores and mood discovery</strong></summary>
<br />

![Algorithmic match and mood discovery UI concept](project%20images/JioHotstar%20Algorithmic%20UI%20Demo.png)

</details>

## How success could be measured

The PRD proposes the following metrics. Baselines, event definitions, and targets need validation before an experiment:

| Metric | Definition | Purpose |
|---|---|---|
| **Session-to-play conversion** | Sessions with a title watched for at least 5 minutes | North star |
| **Average time-to-play (TTP)** | Time from app open to pressing play | Primary indicator; the brief suggests under 5 minutes |
| **Zero-watch session rate** | Sessions that end without playing a video | Secondary indicator |
| **Early abandonment rate** | Starts exited within the first 3 minutes | Counter metric |

## Product principles

- Treat a match score as a relevance estimate, not a promise of enjoyment.
- Explain recommendation signals in language viewers can understand.
- Exclude personally identifiable information from watch-history model processing, as required by the PRD.
- Keep recommendations from blocking standard discovery; omit the score when the service is unavailable.
- Measure satisfying starts, not just clicks.

## Project status

- [x] Product brief and initial responsive screen concepts
- [x] Product context and delivery plan
- [ ] Validate target audience, baseline metrics, and success thresholds
- [ ] Test the discovery flow with representative viewers
- [ ] Validate match-score methodology and explanation content
- [ ] Build and measure an instrumented implementation

## Repository contents

```text
.
├── README.md
├── context.md
├── plan.md
├── JioHotstar PRD.docx
├── project images/
└── prototype/
    ├── mobile screen/
    └── web screen/
```

## Source and assumptions

The original product requirements are in [`JioHotstar PRD.docx`](./JioHotstar%20PRD.docx). The persona, journey, empathy map, and target values in that brief are incomplete; they are treated as open discovery work rather than established research. See [context.md](./context.md) for scope and assumptions and [plan.md](./plan.md) for the proposed delivery sequence.
