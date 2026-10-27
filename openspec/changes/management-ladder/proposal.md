# Proposal

## Why

`on_call.md` asks for an EM3. The career ladder names a Management track and gives it no levels. In career skills, IC4 and IC5 are the same row.

## What Changes

- On the career ladder and on career skills, list the management track as M1, M2, M2 (SEM), M3 (Director), M4 (VPE), and M5 (CTO), in that order.
- Make IC5 differ from IC4 on system design and on scope past a single team.
- In `on_call.md`, replace EM3 with M2 (SEM). M3 is Director, so the rotating incident manager paired with IC3 is the senior manager title, not the Director.

## Capabilities

### New Capabilities

- `management-ladder`: Management levels from M1 to M5 (CTO), and an IC5 bar that is not a copy of IC4.

### Modified Capabilities

None. `openspec/specs/` is empty.

## Impact

Files: `public/organisation/career-ladder.md`, `public/organisation/career-skills.md`, `public/engineering/on_call.md`.

Depends on nothing. Blocks `hiring-loop`, `promotion-and-underperformance`, and `management-interfaces`.

Links: `on_call.md` keeps the IC3 pairing and drops the stale EM3 name. `unify-rating-scales` is a separate scale change and does not define these levels.
