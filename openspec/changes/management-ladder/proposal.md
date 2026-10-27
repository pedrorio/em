# Proposal

## Why

`on_call.md` asks for an EM3. The career ladder names a Management track and gives it no levels. In career skills, IC4 and IC5 are the same row.

## What Changes

- On the career ladder and on career skills, list exactly five management levels: M1, M2, M3 (Director), M4 (VPE), and M5 (CTO), in that order. Senior EM is not its own level.
- Make IC5 differ from IC4 on system design and on scope past a single team.
- Pair M1 with IC4 on the career skills table and on the on-call roster. Where `on_call.md` says IC3 or EM3, it says IC4 or M1.

## Capabilities

### New Capabilities

- `management-ladder`: Management levels from M1 to M5 (CTO), and an IC5 bar that is not a copy of IC4.

### Modified Capabilities

None. `openspec/specs/` is empty.

## Impact

Files: `public/organisation/career_ladder.md`, `public/organisation/career_skills.md`, `public/engineering/on_call.md`.

Depends on nothing. Blocks `hiring-loop`, `promotion-and-underperformance`, and `management-interfaces`.

Links: `on_call.md` drops EM3 and IC3 as the manager pair. M1 is the pair of IC4. `unify-rating-scales` is a separate scale change and does not define these levels.
