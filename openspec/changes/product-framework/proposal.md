# Proposal

## Why

Discovery already runs market, then feature, then a test plan between the PRD and the RFC. The PRD and the test plan are missing. The existing market file also holds product vision and feature capabilities, so two rungs are one document. Standups and the engineering group name a PRD that is not in the repo.

## What Changes

- Narrow `public/product/mrd.md` to segments and expansion. Move unit economics to the business case and features to the PRD.
- Add `public/product/brd.md`, titled "Business case". It focuses on the user and the business: unit economics and value proposition. It is not an enterprise IT requirements list. It may be the same case as the domain business case, or a separate one. When the domain is new and the product or platform already exists, the two stay separate.
- Add `public/product/prd.md` for one segment's needs and the features that serve them. It points at the market segment and the business case.
- Add `public/product/test_plan.md` tying that PRD to an RFC.
- Point the PRD mentions in `engineering_group.md`, `standups.md`, and `knowledge/organisation/discovery.md` at `prd.md`.
- Link the four from the readme under Product, with readable titles.

## Capabilities

### New Capabilities

- `product-chain`: Market, business model, feature, and the test plan that ties a feature to an RFC.

### Modified Capabilities

None. `openspec/specs/` is empty.

## Impact

Files: `public/product/mrd.md` (narrow), `public/product/brd.md`, `public/product/prd.md`, `public/product/test_plan.md`, `readme.md`, `public/organisation/engineering_group.md`, `public/project/standups.md`, `knowledge/organisation/discovery.md`.

Depends on `naming-and-structure-pass` for the `mrd.md` path and the rung names.

Links: `planning-chain` holds the domain and staffing case. The two cases are one document or two, depending on the situation. The three public PRD sites are the engineering group ownership table, the engineering group discovery workflow, and standups. Discovery is the fourth mention, in the knowledge note.

Not split: the four documents are one chain, and the dangling PRD names only make sense once the PRD exists.
