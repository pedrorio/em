# Spec Delta

## Purpose

Defines the management track the on-call roster already assumes, and separates the top two IC levels that are currently the same row.

## ADDED Requirements

### Requirement: Management track lists five levels
The career ladder SHALL list EM1, EM2, EM3, Senior EM, and Director, in that order, on the management track. EM3 MUST be the level an incident manager can hold. The ladder MUST NOT add Head of Engineering or CTO in this change.

#### Scenario: Reader finds EM3
- **WHEN** a reader looks up the EM3 named in the on-call roster
- **THEN** the career ladder lists EM3 between EM2 and Senior EM, and Director is the top level shown

### Requirement: IC5 is not a copy of IC4
Career skills SHALL give IC5 a higher bar than IC4 on system design and on scope beyond one team. The two rows MUST NOT match in every column.

#### Scenario: Reader compares IC4 and IC5
- **WHEN** a reader reads the engineering skills table
- **THEN** IC5 differs from IC4 on system design and on scope, and the other columns are not a duplicate row
