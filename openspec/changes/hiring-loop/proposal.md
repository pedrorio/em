# Proposal

## Why

The repo has no hiring template. Onboarding in the engineering group already lists expectations at 7, 21, and 63 days, and nothing feeds that list.

## What Changes

- Add `public/people/hiring.md` with three parts: scorecard, interview plan, and debrief.
- The scorecard records evidence against one named ladder level and a hire or no-hire decision. It does not reuse the four-point skill scale.
- The debrief states what the new hire must know by day 7, day 21, and day 63, and points at the existing onboarding list. Do not add a new onboarding template.
- Link it from the readme under People, with the title "Hiring".

## Capabilities

### New Capabilities

- `hiring`: The scorecard, interview plan, and debrief that feed the existing 7, 21, and 63 day onboarding list.

### Modified Capabilities

None. `openspec/specs/` is empty.

## Impact

Files added: `public/people/hiring.md`. Files touched: `readme.md`. `engineering-group.md` is referenced and not rewritten.

Depends on `management-ladder` for the level names. Does not depend on `unify-rating-scales`.

Links: the debrief writes into the 7, 21, and 63 day expectations already in `engineering-group.md`.
