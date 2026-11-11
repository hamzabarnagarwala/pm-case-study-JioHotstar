# Product Context

## Product

**Working title:** JioHotstar Discovery — Find Your Next Watch  
**Project type:** Independent portfolio product concept  
**Surface area:** Existing streaming discovery experience on mobile and web

This concept addresses decision friction in a large streaming catalog. The proposed direction is to help viewers recognize relevant titles sooner by making personalized recommendations more visible and explainable, while keeping familiar browsing patterns intact.

## Problem statement

The PRD describes casual subscribers spending an average of approximately 15 minutes browsing before finding something to watch. Some sessions end without any video being played. The working hypothesis is that choice overload and low confidence in what to pick contribute to slow discovery and disengagement.

These are problem statements and baseline claims from the supplied PRD; they have not been independently verified in this project.

## Target user

The PRD identifies a **casual JioHotstar subscriber** who wants to find something that fits their current mood without scrolling through a large catalog. It does not contain a completed persona or user-research evidence.

### Working user need

> When I have limited time to watch, help me quickly spot titles that are likely to suit me and explain why they were recommended.

Treat this as a hypothesis to validate, not a research finding. Questions for discovery include:

- Which viewers experience the most browsing friction, and in what situations?
- What signals make a recommendation feel relevant or untrustworthy?
- Do viewers understand what a match percentage means?
- Which controls are useful for shared, family, or profile-based viewing?
- How should the experience serve viewers with little or no watch history?

## Product direction

Show an at-a-glance match percentage on title cards, with an optional explanation of the factors contributing to that score. Mood-led collections can provide another way to narrow discovery without replacing the catalog or turning the experience into a short-video feed.

The percentage is a **relevance estimate**, not a guarantee that a viewer will enjoy a title. Score meaning, calibration, and explanation language need validation before release.

## Scope

### Initial focus

- Display a title's match percentage in the default, unexpanded thumbnail/card view.
- Provide an accessible interaction to explain relevant recommendation signals.
- Keep score delivery fast and avoid blocking the rest of the discovery experience.
- Gracefully omit match scores and retain standard discovery if the recommendation service is unavailable.
- Explore mood-based collections as a secondary discovery aid.

### Non-goals

- A short-form, swipeable trailer feed.
- Shrinking the catalog or removing niche categories.
- Acquiring additional content to solve the discovery problem.
- A complete redesign of the core home screen.

## Requirements from the PRD

### Functional

1. Calculate and display a match percentage using watch behavior, explicitly expressed preferences, and title metadata.
2. Provide an explanation of the factors behind the score when the viewer asks for it.
3. Make the score visible without requiring a click or expanding the title card.

### Non-functional

- Render the score alongside the thumbnail in under 200 ms.
- Pre-calculate/cache scores for the top 500 trending catalog items per active user session.
- If the recommendation service times out, show the standard UI without a score; do not block the session.
- Strip personally identifiable information from watch history during model processing.

These are PRD requirements, not verified system capabilities. The implementation and measurement approach still need technical discovery.

## Success measures

| Measure | Definition in the PRD | Intended interpretation |
|---|---|---|
| Session-to-play conversion | Sessions in which a viewer watches a movie or series for at least 5 minutes | North-star measure of successful discovery |
| Average time-to-play | Time from app open to pressing play | Primary indicator; the PRD proposes reducing it from about 15 minutes to under 5 minutes |
| Zero-watch session rate | Sessions that end without any video being played | Secondary indicator of unsuccessful discovery |
| Early abandonment rate | Starts exited within the first 3 minutes | Counter metric to guard against low-quality clicks |

Instrument these consistently and compare against a measured baseline. A target should not be treated as approved until the PRD's placeholder and baseline are resolved.

## Prioritization and open questions

The PRD prioritizes algorithmic match-quality scoring as P0, semantic search as P1, short-form trailer feeds as P2, and mood hubs as P3. Since short-form feeds are also explicitly a non-goal, this project excludes them and follows the non-goal. Mood hubs are considered secondary to the P0 score experience.

Before implementation or evaluation, resolve:

1. What is the approved time-to-play target? The PRD contains an example placeholder, not a final value.
2. What are the current baselines and measurement windows for all four success metrics?
3. Which audience and viewing contexts should the first test represent?
4. How is a match score calculated, calibrated, and explained, especially for new users?
5. What is the privacy-safe event/data model and retention policy?
6. What happens when multiple profiles or shared household devices affect watch signals?
7. Is semantic search in scope for a later phase, and what evidence would justify it?

## Current artifacts

- `JioHotstar PRD.docx` — supplied product brief.
- `prototype/mobile screen/` — mobile HTML concept, design notes, and screenshot.
- `prototype/web screen/` — web HTML concept, design notes, and screenshot.

The prototypes demonstrate interface direction only. Their visible scores and recommendation explanations are illustrative and are not backed by a live model or validated user data.
