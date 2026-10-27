# Proposal

## Why

The program increment asks for a Business Review and then lists ideas. There is no annual plan, no domain business case, and no initiative sized by effort and return.

## What Changes

- Add `public/organisation/annual_plan.md` for the year and the budget.
- Add `public/organisation/domain_business_case.md` for one domain: discovery, opportunities, levers, and the ask. State that it is not `brd.md`.
- Treat `program-increment.md` as the quarterly plan. Its inputs are the annual plan and the domain business cases. Keep the existing Roadmaps bullet as the roadmap output. Do not add a roadmap template.
- Add `public/project/initiative.md` with kind (product, tech, or quality), effort, and ROI.
- Link the new files from the readme with readable titles. Do not rename `program-increment.md`.

## Capabilities

### New Capabilities

- `planning-chain`: Annual plan and budget, domain business case, quarterly program increment, and sized initiatives.

### Modified Capabilities

None. `openspec/specs/` is empty.

## Impact

Files added: `public/organisation/annual_plan.md`, `public/organisation/domain_business_case.md`, `public/project/initiative.md`. Files touched: `public/organisation/program-increment.md`, `readme.md`.

Depends on `naming-and-structure-pass`. Depends on `product-framework` so the domain business case is not confused with `brd.md`.

Links: `engineering-strategy` sets headcount, budget, and delivery constraints this chain spends. `domain-ownership-and-capacity` describes what the same domain runs. `finish-stub-docs` does not edit the program increment.

Not split: the four rungs are one sequence. The roadmap stays an output of the quarterly plan because `program-increment.md` already lists it.
