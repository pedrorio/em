# Proposal

## Why

Nothing sits between the vision and the program increment. A reader cannot see tech debt, headcount, budget, or delivery metrics.

## What Changes

- Add `public/organisation/engineering_strategy.md` as a one-pager with those four sections.
- It takes `vision.md` as the vision for a domain, a business, or a platform. It does not restate that vision, and it does not add a company vision. A company vision would say how products, platforms, and domains tie together, and it is a different document.
- Where it names the system document, it says architecture document.
- Link it from the readme between Vision and Program increment, as "Engineering strategy".
- Do not add a roadmap file here.

## Capabilities

### New Capabilities

- `engineering-strategy`: The one-pager between vision and the quarterly plan covering tech debt, headcount, budget, and delivery metrics.

### Modified Capabilities

None. `openspec/specs/` is empty.

## Impact

Files added: `public/organisation/engineering_strategy.md`. Files touched: `readme.md`.

Depends on `naming-and-structure-pass` only for the architecture document name.

Links: `planning-chain` owns the annual budget, the roadmap, and the domain case. This one-pager states the constraints those plans take. `vision.md` is the domain, business, or platform vision and is not rewritten.
