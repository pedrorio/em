# Proposal

## Why

The engineering group lists products and components. The reorg note lists manager ratios. Nothing says which systems a domain owns, what maintenance costs, or how that team grows or shrinks.

## What Changes

- Add `public/organisation/domain.md` with systems owned, maintenance load, current capacity, scale up, and scale down.
- Scale up and scale down point at `reorg.md` for ratios and rollout. Do not copy that note.
- Do not replace the engineering group ownership tables. They stay the product and component lists.
- Link it from the readme under Organisation, as "Domain".

## Capabilities

### New Capabilities

- `domain-capacity`: What a domain owns, what it costs to maintain, and how its team scales.

### Modified Capabilities

None. `openspec/specs/` is empty.

## Impact

Files added: `public/organisation/domain.md`. Files touched: `readme.md`.

Depends on `planning-chain` so "domain" matches the business case.

Links: `reorg.md` stays the rollout note. `engineering_group.md` stays the product and component tables. Staffing stays on `public/organisation/business_case.md` in `planning-chain`. `operational-reviews` reviews this domain. It does not define ownership.
