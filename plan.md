# Product Plan

This plan turns the supplied PRD and early screen concepts into a testable, portfolio-ready product case study. It is intentionally staged: validate the problem and score semantics before treating the prototype as a build specification.

## Guiding outcome

Help viewers find a title worth watching with less browsing, while maintaining or improving the quality of starts. The north-star measure is session-to-play conversion, with time-to-play as the primary indicator and early abandonment as a counter metric.

## Phase 1 — Resolve product questions

- Confirm target users and the contexts in which browsing feels difficult.
- Establish baseline definitions, instrumentation, measurement window, and the approved time-to-play target.
- Decide what signals can contribute to a score and how to explain them accurately.
- Define behavior for viewers with limited history, shared profiles, and unavailable scores.
- Reconcile the prioritization list with non-goals: keep short-form trailer feeds out of scope.

**Exit criteria:** A reviewed product brief with measurable baseline/target definitions, audience scope, score principles, privacy constraints, and no contradictory scope items.

## Phase 2 — Validate the experience

- Review the mobile and web concepts against the P0 match-score and transparency requirements.
- Test whether viewers notice and understand the percentage without prompting.
- Test whether the explanation improves confidence without adding material discovery friction.
- Check mood-based collections as an optional aid, not a replacement for core recommendations.
- Include accessibility, localization, and profile/shared-device scenarios in evaluation.

**Exit criteria:** Evidence-backed changes to the flow, comprehension of what a score does and does not mean, and a documented decision on whether mood hubs belong in the first implementation.

## Phase 3 — Define a measurable MVP

### Proposed MVP

1. Display a match percentage on eligible title cards.
2. Offer a clear, accessible explanation of the meaningful signals behind that score.
3. Keep standard catalog browsing available when no score is available.
4. Return the standard discovery UI when scoring is slow or unavailable.
5. Instrument recommendation exposure, explanation use, play starts, 5-minute watches, time-to-play, early abandonment, and zero-watch sessions.

### Reliability, privacy, and performance checks

- Verify the under-200-ms score-rendering requirement under representative conditions.
- Validate the top-500 trending-item caching requirement and its freshness/capacity assumptions.
- Verify that recommendation processing excludes PII and document data handling and retention.
- Exercise timeout and missing-score cases; they must not block standard discovery.
- Avoid implying that a score is a probability or guarantee unless the scoring method supports that claim.

**Exit criteria:** A testable MVP specification, privacy review, measurable event definitions, and agreed reliability/performance checks.

## Phase 4 — Build, instrument, and evaluate

- Implement behind a controlled rollout or experiment where appropriate.
- Validate data quality and fallback behavior before interpreting product outcomes.
- Compare session-to-play conversion, time-to-play, and zero-watch rate against the agreed baseline.
- Monitor early abandonment as a guardrail, alongside reliability and latency.
- Segment results only where sample size, privacy, and experiment design support meaningful conclusions.

**Exit criteria:** A documented decision to iterate, expand, or stop based on pre-agreed metrics and guardrails.

## Prioritization

| Priority | Candidate | Plan |
|---|---|---|
| P0 | Algorithmic match-quality score | Core MVP; validate score quality and explanation |
| P1 | AI-powered semantic search | Defer until evidence shows the core score experience leaves a meaningful discovery gap |
| P2 | Short-form trailer feed | Excluded; conflicts with the PRD non-goal |
| P3 | Granular mood hubs | Consider as a follow-up; validate usefulness and avoid crowding the home screen |

The supplied PRD assigns these relative priorities but does not include numeric RICE inputs or validated effort estimates.

## Risks and mitigations

| Risk | Mitigation |
|---|---|
| A precise-looking percentage is misunderstood as a guarantee | Explain its meaning and inputs; test comprehension; avoid unsupported probability language |
| Weak or sparse history produces poor matches | Define cold-start behavior and retain standard discovery |
| Fast starts do not represent satisfying choices | Monitor early abandonment and 5-minute watches alongside time-to-play |
| Recommendation latency degrades the home experience | Cache where appropriate and fall back without blocking |
| Sensitive viewing data is exposed or used unexpectedly | Minimize and de-identify processing data; review access, retention, and consent |
| Additional mood UI increases complexity | Validate it separately and keep the first release centered on P0 |

## Deliverables and status

- [x] PRD-derived project context
- [x] Initial mobile and web HTML concepts
- [x] Project README and delivery plan
- [ ] Validated personas, journey, and research insights
- [ ] Approved metric baselines, targets, and event definitions
- [ ] Tested prototype and accessibility findings
- [ ] MVP technical design and privacy review
- [ ] Instrumented implementation and outcome readout

## Portfolio case-study checklist

When presenting the work, distinguish source requirements, design hypotheses, prototype behavior, and measured outcomes. Do not claim user validation or business impact until research or a live experiment supports those claims.
