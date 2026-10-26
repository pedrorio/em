# Spec Delta

## Purpose

Orders annual planning, domain funding, the quarterly program increment, and the initiatives that increment commits to.

## ADDED Requirements

### Requirement: Annual plan covers the year and the budget
`public/organisation/annual-plan.md` SHALL cover the year's plan and the budget. The readme SHALL link it as "Annual plan".

#### Scenario: Reader opens the annual plan
- **WHEN** a reader opens the annual plan
- **THEN** it has a plan for the year and a budget

### Requirement: Domain business case is not the product business case
`public/organisation/domain-business-case.md` SHALL cover discovery, opportunities, levers, and the funding ask for one domain. It MUST say it is not the product business case in `brd.md`. The readme SHALL link it as "Domain business case".

#### Scenario: Reader compares the two business cases
- **WHEN** a reader opens the domain business case
- **THEN** it is about one domain's funding and it points away from `public/product/brd.md`

### Requirement: Program increment is the quarterly plan
`program-increment.md` SHALL name the annual plan and the domain business cases as inputs, and SHALL keep Roadmaps as an output. This change MUST NOT add a separate roadmap template and MUST NOT rename the file.

#### Scenario: Reader starts a quarter
- **WHEN** a reader opens the program increment
- **THEN** the inputs include the annual plan and domain business cases, and roadmaps remain a communication output

### Requirement: Initiative is sized
`public/project/initiative.md` SHALL record a kind of product, tech, or quality, plus effort and ROI. The readme SHALL link it as "Initiative".

#### Scenario: Reader opens an initiative
- **WHEN** a reader opens the initiative template
- **THEN** it asks for product, tech, or quality, and for effort and ROI
