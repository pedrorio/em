# Proposal

## Why

The post-mortem has an Action Items heading and no owner, date, or status. Nothing can tell whether an action was done.

## What Changes

- On `public/project/post-mortem.md`, each action item has an owner, a due date, and a status.
- Do not edit `retro.md` here. `finish-stub-docs` is where open actions are reviewed.
- Do not add a second incident template.

## Capabilities

### New Capabilities

- `postmortem-actions`: Post-mortem action items that a later review can check.

### Modified Capabilities

None. `openspec/specs/` is empty.

## Impact

Files: `public/project/post-mortem.md`.

Depends on nothing. Blocks the retrospective part of `finish-stub-docs`.

Links: `operational-reviews` may list open actions. It does not define this format. `security-practice` sends security incidents through this same post-mortem.
