# Tasks

## 1. Names

- [ ] 1.1 Rename `public/product/MRD.md` to `public/product/mrd.md` and point the readme link at the new path. Verify `git grep MRD.md` finds nothing and the file body is unchanged.
- [ ] 1.2 In `knowledge/organisation/discovery.md`, replace the ADR system-documentation line with architecture document, and name the market, business-model, and feature rungs. Verify the file no longer contains ADR or ARD.
- [ ] 1.3 In `public/organisation/engineering-group.md`, replace the ARD ownership column and the ARD workflow bullet with architecture document. Verify the file no longer contains ARD.
- [ ] 1.4 Confirm `program-increment.md` still says Architectural Review, and confirm the only public rename is `MRD.md` to `mrd.md`. Verify with `git diff --stat`.
