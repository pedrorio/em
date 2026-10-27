# Proposal

## Why

`retro.md` is an empty three-column table. `goals.md` does not say whose goals they are. `performance_review.md` stops at the rating grid. The program increment is thin as well, and `planning-chain` owns that file, so it is not in this change.

## What Changes

- `retro.md`: add the team and the date, keep Went well, To improve, and Action points, and add a place to review open post-mortem actions.
- `goals.md`: say these are one person's goals. Keep owner, reporter, dates, objective, and key results, and name the ladder dimension.
- `performance_review.md`: keep self, manager, and perception gap. Keep the expectation ratings from `unify-rating-scales`. Name the outcome as a promotion case, an underperformance plan, or no change.
- Do not edit `program_increment.md`.

## Capabilities

### New Capabilities

- `retrospective`: A retrospective that can review open post-mortem actions.
- `individual-goals`: One person's goals, distinct from a team or domain review.
- `performance-review`: A review that ends in a promotion case, an underperformance plan, or no change.

### Modified Capabilities

None. `openspec/specs/` is empty.

## Impact

Files: `public/project/retro.md`, `public/people/goals.md`, `public/people/performance_review.md`.

Depends on `unify-rating-scales`, `postmortem-follow-up`, and `promotion-and-underperformance`.

Links: `operational-reviews` covers team and domain goals, so this goals file stays individual. `planning-chain` covers the program increment.
