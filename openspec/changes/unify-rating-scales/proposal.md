# Proposal

## Why

Performance review lists seven ratings. The performance scale is four expectation ratings, and it is not the skill scale.

## What Changes

- Change the performance review gap line to Unable to Meet Expectations, Meets Expectations, Often Exceeds, and Redefines Expectations.
- Leave `career_skills.md` and `learning_and_development.md` on Untrained, Basic, Intermediate, and Advanced.
- Do not use the expectation ratings for a hire or no-hire decision. That stays in `hiring-loop`.

## Capabilities

### New Capabilities

- `rating-scale`: The four expectation ratings used on a performance review.

### Modified Capabilities

None. `openspec/specs/` is empty.

## Impact

Files: `public/people/performance_review.md`.

Depends on nothing. Blocks `promotion-and-underperformance` and the performance-review part of `finish-stub-docs`.

Links: `hiring-loop` records a hire decision against a ladder level and does not use these expectation ratings. `promotion-and-underperformance` cites this scale.
