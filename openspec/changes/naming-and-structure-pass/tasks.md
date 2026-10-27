# Tasks

## 1. Names

- [ ] 1.1 Rename `public/product/MRD.md` to `public/product/mrd.md` and point the readme link at the new path. Verify `git grep MRD.md` finds nothing and the file body is unchanged.
- [ ] 1.2 In `knowledge/organisation/discovery.md`, replace the ADR system-documentation line with architecture document, and name the market, business-model, and feature rungs. Verify the file no longer contains ADR or ARD.
- [ ] 1.3 In `public/organisation/engineering_group.md`, replace the ARD ownership column and the ARD workflow bullet with architecture document. Verify the file no longer contains ARD.
- [x] 1.4 Rename `architecture-doc.md`, `career-ladder.md`, `career-skills.md`, `engineering-group.md`, `program-increment.md`, and `post-mortem.md` to snake_case, and point the readme at the new paths. Verify no public template file name contains a hyphen, and that `program_increment.md` still says Architectural Review.
