# Proposal

## Why

`knowledge/project/time.md` describes an operations review and there is no template. A team review and a domain review are the same shape at two scopes, so they are one template.

## What Changes

- Add `public/organisation/operational_review.md` with a team section and a domain section.
- Each section covers goals, metrics, and KPIs, and points at `goals_signals_metrics.md` for the shape.
- Individual goals stay in `people/goals.md`. This change does not edit that file.
- Add one pointer from `knowledge/project/time.md` to the new template.
- Link it from the readme under Organisation, as "Operational review".

## Capabilities

### New Capabilities

- `operational-reviews`: A team review and a domain review, each with goals, metrics, and KPIs.

### Modified Capabilities

None. `openspec/specs/` is empty.

## Impact

Files added: `public/organisation/operational_review.md`. Files touched: `readme.md`, `knowledge/project/time.md`.

Depends on `domain-ownership-and-capacity` for the domain being reviewed. The metric shape is the existing `goals_signals_metrics.md`.

Links: `finish-stub-docs` says `goals.md` is one person's goals, so this review does not become a second individual OKR. `postmortem-follow-up` keeps action status on the post-mortem. This review can list open actions later. It does not own that format.
