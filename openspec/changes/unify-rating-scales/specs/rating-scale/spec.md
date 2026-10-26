# Spec Delta

## Purpose

Makes skill ratings in the performance review use the same four points already printed on the career skills and learning templates.

## ADDED Requirements

### Requirement: Performance review uses the four-point scale
The performance review template SHALL rate a skill as Untrained, Basic, Intermediate, or Advanced. It MUST NOT list a second scale.

#### Scenario: Reviewer rates a skill
- **WHEN** a reviewer fills the performance review gap table
- **THEN** the only ratings shown are Untrained, Basic, Intermediate, and Advanced

### Requirement: Skill templates keep the same four points
Career skills and learning and development SHALL keep Untrained, Basic, Intermediate, and Advanced as their scale.

#### Scenario: Reader compares the people templates
- **WHEN** a reader compares the performance review with career skills and with learning and development
- **THEN** all three show the same four ratings
