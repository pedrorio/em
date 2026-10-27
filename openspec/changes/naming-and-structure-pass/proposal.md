# Proposal

## Why

One system document is called ADR, ARD, and architecture document. `MRD.md` is the only uppercase file name, next to `rfc.md`. Later changes add files, so the names have to be fixed first.

## What Changes

- Rename `public/product/MRD.md` to `public/product/mrd.md` and update the readme target. Leave the section body for `product-framework`.
- In `knowledge/organisation/discovery.md`, replace "ADR (system documentation)" with "architecture document", and name the rungs once: market (`mrd`), business model (`brd`), feature (`prd`). Do not add those files here.
- In `public/organisation/engineering_group.md`, replace the ARD column and the ARD workflow bullet with "architecture document".
- Rename existing hyphenated public templates to snake_case, and point the readme at the new paths. Leave each file body unchanged:
  - `architecture-doc.md` to `architecture_doc.md`
  - `career-ladder.md` to `career_ladder.md`
  - `career-skills.md` to `career_skills.md`
  - `engineering-group.md` to `engineering_group.md`
  - `program-increment.md` to `program_increment.md`
  - `post-mortem.md` to `post_mortem.md`
- New public templates use snake_case. A short acronym with no extra word stays lowercase, as `rfc.md` and `mrd.md`.
- Leave "Architectural Review" in `program_increment.md`. That is a meeting, not the architecture document.
- Do not add links from `knowledge/` notes to `public/` templates. That split stays.

## Capabilities

### New Capabilities

- `document-names`: One name for the architecture document, one name for each product rung, and one file-name rule for new templates.

### Modified Capabilities

None. `openspec/specs/` is empty.

## Impact

Files: `public/product/MRD.md` (rename to `mrd.md`), `readme.md`, `knowledge/organisation/discovery.md`, `public/organisation/engineering_group.md`, and the six hyphenated renames listed above.

Depends on nothing. Blocks `product-framework` and any later file that would otherwise say ADR or ARD.

Links: `product-framework` fills `mrd`, `brd`, and `prd`. `engineering-strategy` and `planning-chain` use "architecture document" and do not revive ADR.
