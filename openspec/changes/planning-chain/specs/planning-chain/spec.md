# Spec Delta

## Purpose

Orders the annual plan, the domain and staffing case, the roadmap, and the initiatives those plans commit to.

## ADDED Requirements

### Requirement: Annual plan covers the year and the budget
`public/organisation/annual_plan.md` SHALL cover the year's plan and the budget. The readme SHALL link it as "Annual plan".

#### Scenario: Reader opens the annual plan
- **WHEN** a reader opens the annual plan
- **THEN** it has a plan for the year and a budget

### Requirement: Domain business case focuses on the domain and staffing
`public/organisation/domain_business_case.md` SHALL cover one domain and its staffing, including discovery, opportunities, levers, and the ask. It is a different lens from the user-and-business case in `brd.md`. The two MAY be one case. When the domain is new and the product or platform already exists, they MUST be separate documents. The readme SHALL link it as "Domain business case".

#### Scenario: New domain on an existing platform
- **WHEN** the domain is new and the product or platform already exists
- **THEN** the domain business case stays separate from `public/product/brd.md`

### Requirement: Roadmap is its own template
`public/organisation/roadmap.md` SHALL name the domain, product, or platform it covers, the horizon, what is on it, and what is not on it. The engineering group status line, the program increment Roadmaps line, and the pulse roadmap line SHALL point at it. This change MUST NOT remodel `program_increment.md`. The readme SHALL link it as "Roadmap".

#### Scenario: Reader follows a roadmap mention
- **WHEN** a reader follows the roadmap mention in the engineering group, the program increment, or the pulse
- **THEN** the target is `public/organisation/roadmap.md`

### Requirement: Initiative is sized
`public/project/initiative.md` SHALL record a kind of product, tech, or quality, plus effort and ROI. The readme SHALL link it as "Initiative".

#### Scenario: Reader opens an initiative
- **WHEN** a reader opens the initiative template
- **THEN** it asks for product, tech, or quality, and for effort and ROI
