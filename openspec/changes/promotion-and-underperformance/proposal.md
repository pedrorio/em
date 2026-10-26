# Proposal

## Why

After hiring, the people templates jump to a goals stub. There is no promotion case and no underperformance path. They use the same evidence, so they stay one change and two templates.

## What Changes

- Add `public/people/promotion.md` for a case to the next ladder level.
- Add `public/people/underperformance.md` for the gap, the support, and the next review date.
- Both cite a current ladder level and the four-point scale. They point at `goals.md` and `performance_review.md` and do not rewrite them.
- Link both from the readme under People, as "Promotion" and "Underperformance".

## Capabilities

### New Capabilities

- `career-decisions`: The promotion case and the underperformance plan, both tied to a ladder level.

### Modified Capabilities

None. `openspec/specs/` is empty.

## Impact

Files added: `public/people/promotion.md`, `public/people/underperformance.md`. Files touched: `readme.md`.

Depends on `management-ladder` and `unify-rating-scales`. `finish-stub-docs` later makes the goals and performance review templates less thin. It does not replace these two files.

Not split: the two decisions share the ladder and the rating, and they are the two outcomes of a review.
