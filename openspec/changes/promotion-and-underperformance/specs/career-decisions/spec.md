# Spec Delta

## Purpose

Gives a promotion case and an underperformance plan that both cite the same ladder and the same expectation ratings.

## ADDED Requirements

### Requirement: Promotion case asks for the next level
`public/people/promotion.md` SHALL name the current level, the next level, and the evidence on the expectation ratings. The readme SHALL link it as "Promotion".

#### Scenario: Manager writes a promotion case
- **WHEN** a manager opens the promotion template
- **THEN** it asks for the current level, the next level, and evidence rated Unable to Meet Expectations, Meets Expectations, Often Exceeds, or Redefines Expectations

### Requirement: Underperformance plan has support and a date
`public/people/underperformance.md` SHALL name the current level, the gap on the expectation ratings, the support, and the next review date. The readme SHALL link it as "Underperformance".

#### Scenario: Manager opens an underperformance plan
- **WHEN** a manager opens the underperformance template
- **THEN** it asks for the level, the gap, the support, and a review date

### Requirement: Both point at goals and the performance review
Each template SHALL point at the individual goals template and the performance review template, and MUST NOT copy their tables.

#### Scenario: Reader follows the evidence
- **WHEN** a reader looks for the evidence behind either decision
- **THEN** the template points at individual goals and the performance review
