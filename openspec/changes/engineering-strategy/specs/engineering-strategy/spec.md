# Spec Delta

## Purpose

Puts a one-page engineering strategy between the vision and the program increment so tech debt, headcount, budget, and delivery metrics have a home.

## ADDED Requirements

### Requirement: Strategy one-pager has four sections
`public/organisation/engineering_strategy.md` SHALL contain tech debt, headcount, budget, and delivery metrics. It MUST NOT restate the vision statement or the quarterly plan. The readme SHALL list it between Vision and Program increment as "Engineering strategy".

#### Scenario: Reader looks between vision and the program increment
- **WHEN** a reader moves from Vision to Program increment in the readme
- **THEN** Engineering strategy sits between them and the template has those four sections

### Requirement: Strategy takes a domain, business, or platform vision
The strategy SHALL take `public/organisation/vision.md` as the vision for a domain, a business, or a platform. It MUST NOT treat that file as the company vision, and it MUST NOT add a company vision.

#### Scenario: Reader looks for a company vision
- **WHEN** a reader opens the engineering strategy
- **THEN** it points at `vision.md` as a domain, business, or platform vision and does not add a company vision

### Requirement: Strategy uses the architecture document name
If the strategy names the system document, it SHALL call it the architecture document.

#### Scenario: Strategy mentions the system document
- **WHEN** the strategy template refers to the C4 document
- **THEN** it says architecture document and does not say ADR or ARD
