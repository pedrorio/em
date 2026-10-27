# Spec Delta

## Purpose

Splits market, business model, and feature into three templates, and adds the test plan that connects a feature to an RFC.

## ADDED Requirements

### Requirement: Market template covers segments and expansion
`public/product/mrd.md` SHALL cover target segments and expansion. It MUST NOT hold the feature list or the unit economics.

#### Scenario: Reader opens the market template
- **WHEN** a reader opens `public/product/mrd.md`
- **THEN** it covers segments and expansion, and it points feature scope at the PRD and unit economics at the business case

### Requirement: Business case focuses on the user and the business
`public/product/brd.md` SHALL be titled Business case and SHALL cover the user and the business, including unit economics and the value proposition. It is not an enterprise IT requirements list. It MAY be the same case as the domain business case. When the domain is new and the product or platform already exists, it MUST stay a separate document. The readme SHALL link it as "Business case".

#### Scenario: New domain on an existing platform
- **WHEN** the domain is new and the product or platform already exists
- **THEN** the business case stays separate from the domain business case

#### Scenario: One situation needs one case
- **WHEN** the user, the business, and the domain are a single case
- **THEN** the business case may carry both lenses and it says so

### Requirement: PRD covers one segment
`public/product/prd.md` SHALL describe one segment's needs and the features that serve them, and SHALL point at the market template and the business case. The readme SHALL link it as "Product requirements document".

#### Scenario: Reader opens a feature document
- **WHEN** a reader opens `public/product/prd.md`
- **THEN** it names the segment, the needs, and the features, and it points at the market template and the business case

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
