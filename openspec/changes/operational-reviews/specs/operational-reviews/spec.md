# Spec Delta

## Purpose

Provides one operational review template with a team level and a domain level, each covering goals, metrics, and KPIs.

## ADDED Requirements

### Requirement: Review has team and domain levels
`public/organisation/operational-review.md` SHALL have a team section and a domain section. Each section SHALL cover goals, metrics, and KPIs, and SHALL point at the goals, signals, and metrics template. The readme SHALL link it as "Operational review".

#### Scenario: Reader prepares a domain review
- **WHEN** a reader opens the domain section
- **THEN** it asks for goals, metrics, and KPIs and points at the goals, signals, and metrics template

### Requirement: Individual goals stay individual
The operational review MUST NOT replace the individual goals template.

#### Scenario: Reader looks for a person's goals
- **WHEN** a reader needs one person's objectives
- **THEN** the review points away from itself for that, and the individual goals template remains the place
