# Proposal

Status: Implemented

## Why

Pull requests do not check Markdown or links.

## What Changes

- Add `.github/workflows/markdown.yml`, triggered on pull requests.
- Run `markdownlint-cli2` with `.markdownlint.yaml`.
- The config turns off long-line checks (MD013) and inline HTML checks (MD033). It also turns off rules that the existing outline notes fail (blank lines around headings, lists, and tables; repeated headings; more than one top-level heading; a first line that is not a heading; unused reference definitions; single trailing spaces; unpadded tables).
- Run lychee v0.24.2 with `lychee.toml` on Markdown files and `LICENSE`.
- `lychee.toml` excludes `inowland.medium.com` because that host returns 403 to the checker.
- The software engineering triangle image in `public/project/people_scope_timeline_quality.md` used `cdn.substack.com`, which returned 502. The same path on `substackcdn.com` returns the image, so the host in that URL is updated.

## Capabilities

### New Capabilities

None.

### Modified Capabilities

None.

## Impact

`.github/workflows/markdown.yml`, `.markdownlint.yaml`, and `lychee.toml`.
