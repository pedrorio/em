# Spec Delta

## Purpose

Records which systems a domain owns, the maintenance load, the team capacity, and how that team scales up or down.

## ADDED Requirements

### Requirement: Domain template records ownership and capacity
`public/organisation/domain.md` SHALL list the systems the domain owns, the maintenance load, and the current capacity. The readme SHALL link it as "Domain".

#### Scenario: Reader opens a domain
- **WHEN** a reader opens the domain template
- **THEN** it shows systems, maintenance load, and current capacity

### Requirement: Staffing stays on the business case
The domain template SHALL point at `public/organisation/business_case.md` for staffing. It MUST NOT copy that case.

#### Scenario: Reader looks for staffing
- **WHEN** a reader wants the staffing case for a domain
- **THEN** the domain template points at `public/organisation/business_case.md`

### Requirement: Scaling points at the reorg note
The domain template SHALL cover scale up and scale down by pointing at the reorg template. It MUST NOT copy the reorg ratios or rollout steps.

#### Scenario: Reader looks up how a team shrinks
- **WHEN** a reader reads scale down on the domain template
- **THEN** it points at the reorg template and does not restate the rollout steps
