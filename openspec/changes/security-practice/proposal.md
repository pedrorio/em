# Proposal

## Why

The architecture document lists security as a quality attribute. The RFC has no security check. Incidents already end in the post-mortem, so security does not need a second incident write-up.

## What Changes

- Add `public/engineering/security.md` with an owner, what an RFC must show before it is accepted, and the path into the existing post-mortem.
- Point at the architecture document and at `rfc.md`. Do not rewrite either file.
- Link it from the readme under Engineering, as "Security".

## Capabilities

### New Capabilities

- `security-practice`: Who owns security, what an RFC must show, and how a security incident uses the post-mortem.

### Modified Capabilities

None. `openspec/specs/` is empty.

## Impact

Files added: `public/engineering/security.md`. Files touched: `readme.md`.

Depends on nothing. Uses the action format from `postmortem-follow-up` when that change has landed. The post-mortem file can be linked before that format exists.

Links: `architecture_doc.md` stays the quality-attribute home. `rfc.md` stays the design home. This template says what the RFC must show. It does not add a security section to the RFC.
