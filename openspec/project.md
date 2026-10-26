# EM templates

Markdown templates for engineering management. There is no application code.

## Layout

- `public/engineering/`, `public/organisation/`, `public/people/`, `public/product/`, `public/project/`: public templates.
- `knowledge/`: internal working notes that back the public templates. Do not delete this folder.
- `examples/`: anonymised filled-in examples. Empty apart from its README until those examples are written.
- `readme.md`: index of every template under `public/`.
- `LICENSE`: Creative Commons Attribution 4.0 International. Copyright Pedro Araujo.

## Conventions

- British spelling stays as written (for example, organisation, prioritisation, favourites).
- Do not invent template guidance. Empty spots use the line `TODO(Pedro):`.
- Each file under `public/` starts its header, after the first top-level heading, with: Purpose, When to use, Inputs, Output, Common pitfalls, Sources.
- `public/engineering/architecture-doc.md` is the C4 / arc42-style architecture description.
- `public/engineering/adr.md` is the architecture decision record template (Michael Nygard: Title, Status, Context, Decision, Consequences), plus Date, Deciders, and Related links.
- Pull requests run markdownlint and a link check (`.github/workflows/markdown.yml`).

## Changes

Propose a change under `openspec/changes/<name>/proposal.md` before implementing it. The proposal states `Status: Implemented` or `Status: Proposed`. These documentation changes set `skip_specs: true` in `.openspec.yaml`. Tool context for current OpenSpec also lives in `openspec/config.yaml`.
