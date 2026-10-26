# Proposal

Status: Implemented

## Why

Files under `public/` are headings and tables. They do not say what the template is for, when to use it, what goes in, what comes out, common pitfalls, or sources.

## What Changes

- Add this header to every Markdown file under `public/`, after the first top-level heading:
  - Purpose
  - When to use
  - Inputs
  - Output
  - Common pitfalls
  - Sources
- Each section contains only `TODO(Pedro):`.
- Do not write the section text.

## Capabilities

### New Capabilities

None.

### Modified Capabilities

None.

## Impact

Every `public/**/*.md` template, including `public/engineering/adr.md` and `public/engineering/architecture-doc.md`.

## Notes

Implemented as empty placeholders. The section text is not written.
