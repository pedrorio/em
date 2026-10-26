# Proposal

## Why

Nothing sits between the vision and the program increment. A reader cannot see tech debt, headcount, budget, or delivery metrics.

## What Changes

- Add `public/organisation/engineering-strategy.md` as a one-pager with those four sections.
- It takes `vision.md` as the engineering organisation vision and constrains the program increment. It does not restate either document.
- Where it names the system document, it says architecture document.
- Link it from the readme between Vision and Program increment, as "Engineering strategy".
- Do not add a company vision, and do not add a roadmap file here.

## Capabilities

### New Capabilities

- `engineering-strategy`: The one-pager between vision and the quarterly plan covering tech debt, headcount, budget, and delivery metrics.

### Modified Capabilities

None. `openspec/specs/` is empty.

## Impact

Files added: `public/organisation/engineering-strategy.md`. Files touched: `readme.md`.

Depends on `naming-and-structure-pass` only for the architecture document name.

Links: `planning-chain` owns the annual budget detail and the quarterly plan. This one-pager states the constraints those plans take. `vision.md` is treated as the engineering organisation vision and is not rewritten.
