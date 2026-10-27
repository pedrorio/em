# Spec Delta

## Purpose

Splits the market document from the feature document, and adds the test plan that connects a feature to an RFC.

## ADDED Requirements

### Requirement: Market template covers segments and expansion
`public/product/mrd.md` SHALL cover target segments and expansion. It MUST NOT hold the feature list or the unit economics.

#### Scenario: Reader opens the market template
- **WHEN** a reader opens `public/product/mrd.md`
- **THEN** it covers segments and expansion, and it points feature scope at the PRD and unit economics at `public/organisation/business_case.md`

### Requirement: PRD covers one segment
`public/product/prd.md` SHALL describe one segment's needs and the features that serve them, and SHALL point at the market template and `public/organisation/business_case.md`. This change MUST NOT add `brd.md`. The readme SHALL link it as "Product requirements document".

#### Scenario: Reader opens a feature document
- **WHEN** a reader opens `public/product/prd.md`
- **THEN** it names the segment, the needs, and the features, and it points at the market template and `public/organisation/business_case.md`

### Requirement: Existing PRD mentions resolve
The engineering group ownership table, the engineering group discovery workflow, standups, and the discovery note SHALL point their PRD mentions at `public/product/prd.md`.

#### Scenario: Reader follows a PRD mention
- **WHEN** a reader follows a PRD mention in the engineering group, standups, or the discovery note
- **THEN** the link target is `public/product/prd.md`

### Requirement: Test plan connects the PRD to an RFC
`public/product/test_plan.md` SHALL name the PRD and the RFC it covers. The readme SHALL link it as "Test plan".

#### Scenario: Reader checks feature acceptance
- **WHEN** a reader opens the test plan
- **THEN** it names one PRD and one RFC
