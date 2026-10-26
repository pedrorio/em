# Proposal

## Why

Performance review lists seven ratings. Career skills and learning and development list four: Untrained, Basic, Intermediate, Advanced. A later promotion case cannot cite both.

## What Changes

- Change the performance review gap line to Untrained, Basic, Intermediate, Advanced.
- Leave `career-skills.md` and `learning_and_development.md` on that four-point scale.
- Do not use this scale for a hire or no-hire decision. That stays in `hiring-loop`.

## Capabilities

### New Capabilities

- `rating-scale`: The single scale used when a template rates a skill.

### Modified Capabilities

None. `openspec/specs/` is empty.

## Impact

Files: `public/people/performance_review.md`.

Depends on nothing. Blocks `promotion-and-underperformance` and the performance-review part of `finish-stub-docs`.

Links: `hiring-loop` records a hire decision against a ladder level and does not reuse these four words.
