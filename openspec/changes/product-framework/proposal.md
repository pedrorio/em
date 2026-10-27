# Proposal

## Why

Discovery already runs market, then feature, then a test plan between the PRD and the RFC. The PRD and the test plan are missing. The existing market file also holds product vision and feature capabilities, so two rungs are one document. Standups and the engineering group name a PRD that is not in the repo.

## What Changes

- Narrow `public/product/mrd.md` to segments and expansion. Point unit economics at `public/organisation/business_case.md` and features at the PRD.
- Do not add `brd.md`. The business case is the one template in `planning-chain`.
- Add `public/product/prd.md` for one segment's needs and the features that serve them. It points at the market segment and `public/organisation/business_case.md`.
- Add `public/product/test_plan.md` tying that PRD to an RFC.
- Point the PRD mentions in `engineering_group.md`, `standups.md`, and `knowledge/organisation/discovery.md` at `prd.md`.
- Link the market document, the PRD, and the test plan from the readme under Product, with readable titles.

## Capabilities

### New Capabilities

- `product-chain`: Market, feature, and the test plan that ties a feature to an RFC.

### Modified Capabilities

None. `openspec/specs/` is empty.

## Impact

Files: `public/product/mrd.md` (narrow), `public/product/prd.md`, `public/product/test_plan.md`, `readme.md`, `public/organisation/engineering_group.md`, `public/project/standups.md`, `knowledge/organisation/discovery.md`.

Depends on `naming-and-structure-pass` for the `mrd.md` path and the rung names. Depends on `planning-chain` for `public/organisation/business_case.md`.

Links: the market template and the PRD point at that business case. The three public PRD sites are the engineering group ownership table, the engineering group discovery workflow, and standups. Discovery is the fourth mention, in the knowledge note.

Not split: the market document, the PRD, and the test plan are one chain, and the dangling PRD names only make sense once the PRD exists.
