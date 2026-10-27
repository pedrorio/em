# Spec Delta

## Purpose

Replaces the seven performance ratings with four expectation ratings, and leaves the skill scale unchanged.

## ADDED Requirements

### Requirement: Performance review uses expectation ratings
The performance review template SHALL rate performance as Unable to Meet Expectations, Meets Expectations, Often Exceeds, or Redefines Expectations. It MUST NOT list a second performance scale.

#### Scenario: Reviewer rates performance
- **WHEN** a reviewer fills the performance review gap table
- **THEN** the only ratings shown are those four expectation ratings

### Requirement: Skill templates keep their own scale
Career skills and learning and development SHALL keep Untrained, Basic, Intermediate, and Advanced. They MUST NOT replace that scale with the expectation ratings.

#### Scenario: Reader compares skill and performance ratings
- **WHEN** a reader opens career skills and the performance review
- **THEN** career skills still shows Untrained, Basic, Intermediate, and Advanced, and the performance review shows the expectation ratings
