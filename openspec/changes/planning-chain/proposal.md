# Proposal

## Why

The program increment asks for a Business Review and then lists ideas. There is no annual plan, no business case, no roadmap, and no initiative sized by effort and return. The program increment is a SAFe artefact, and Pedro will change that shape later.

## What Changes

- Add `public/organisation/annual_plan.md` for the year and the budget.
- Add `public/organisation/business_case.md` as the only business case template. Its type is one of new business, new product, new business model, new market expansion, new platform, or new domain. Every case fills the same core and is one ask against a line in the annual plan. Each type adds only its own short section. Do not add `brd.md` or `domain_business_case.md`.
- Add `public/organisation/roadmap.md`. Point the existing roadmap mentions at it: the engineering group status line, the program increment Roadmaps line, and the pulse roadmap line. Do not remodel `program_increment.md` into the quarterly plan.
- Add `public/project/initiative.md` with kind (product, tech, or quality), effort, and ROI.
- Link the new files from the readme with readable titles. Do not rename `program_increment.md`.

## Capabilities

### New Capabilities

- `planning-chain`: Annual plan and budget, the one business case template, roadmap, and sized initiatives.

### Modified Capabilities

None. `openspec/specs/` is empty.

## Impact

Files added: `public/organisation/annual_plan.md`, `public/organisation/business_case.md`, `public/organisation/roadmap.md`, `public/project/initiative.md`. Files touched: `public/organisation/program_increment.md`, `public/organisation/engineering_group.md`, `public/people/pulse.md`, `readme.md`.

Depends on `naming-and-structure-pass`. `product-framework` points the market template and the PRD at this business case and does not add `brd.md`.

Links: `engineering-strategy` sets headcount, budget, and delivery constraints this chain spends. `domain-ownership-and-capacity` describes which systems the domain runs and points staffing at this business case. `finish-stub-docs` does not edit the program increment.

Not split: the roadmap is its own template because the program increment is SAFe and will be replaced later. This change only points that file at the roadmap.
