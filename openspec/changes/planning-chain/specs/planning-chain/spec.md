# Spec Delta

## Purpose

Orders the annual plan, the one business case template, the roadmap, and the initiatives those plans commit to.

## ADDED Requirements

### Requirement: Annual plan covers the year and the budget
`public/organisation/annual_plan.md` SHALL cover the year's plan and the budget. The readme SHALL link it as "Annual plan".

#### Scenario: Reader opens the annual plan
- **WHEN** a reader opens the annual plan
- **THEN** it has a plan for the year and a budget

### Requirement: One business case template
`public/organisation/business_case.md` SHALL be the only business case template. It SHALL require a type of new business, new product, new business model, new market expansion, new platform, or new domain. The readme SHALL link it as "Business case". This change MUST NOT add `brd.md` or `domain_business_case.md`.

#### Scenario: Reader starts a case
- **WHEN** a reader opens the business case template
- **THEN** it asks for one of those six types and no other business case file exists

### Requirement: Every case fills the same core
The template SHALL ask for the customer or user, the value, the cost, the staffing change, the expected return, the risks, and the decision asked for. Each case SHALL be one ask against a line in the annual plan.

#### Scenario: Reader fills a case
- **WHEN** a reader completes a business case of any type
- **THEN** those seven core fields are filled and the case names one line in the annual plan

### Requirement: Each type adds only its own section
The template SHALL have one short section per type. New business adds the business being proposed. New product adds the product. New business model adds the model change. New market expansion adds the target market. New platform adds the consumers and the adoption. New domain adds staffing and ownership.

#### Scenario: Reader opens a new domain case
- **WHEN** the type is new domain
- **THEN** the domain section adds staffing and ownership and does not repeat the other types

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
