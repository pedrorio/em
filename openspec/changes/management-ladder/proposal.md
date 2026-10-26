# Proposal

## Why

`on_call.md` asks for an EM3. The career ladder names a Management track and gives it no levels. In career skills, IC4 and IC5 are the same row.

## What Changes

- On the career ladder, list the management track as EM1, EM2, EM3, Senior EM, and Director, in that order.
- On career skills, add those management levels, and make IC5 differ from IC4 on system design and on scope past a single team.
- Do not edit `on_call.md`. EM3 remains the incident-manager level named there.
- Do not add Head of Engineering or CTO to this ladder.

## Capabilities

### New Capabilities

- `management-ladder`: Management levels from EM1 to Director, and an IC5 bar that is not a copy of IC4.

### Modified Capabilities

None. `openspec/specs/` is empty.

## Impact

Files: `public/organisation/career-ladder.md`, `public/organisation/career-skills.md`.

Depends on nothing. Blocks `hiring-loop`, `promotion-and-underperformance`, and `management-interfaces`.

Links: `on_call.md` is the source of the name EM3 and is left unchanged. `unify-rating-scales` is a separate scale change and does not define these levels.
