# Spec Delta

## Purpose

Defines the management track from M1 to CTO, and separates the top two IC levels that are currently the same row.

## ADDED Requirements

### Requirement: Management track lists the M levels
The career ladder SHALL list M1, M2, M2 (SEM), M3 (Director), M4 (VPE), and M5 (CTO), in that order. M2 (SEM) is the senior manager title. M3 is Director. M4 is VPE. M5 is CTO.

#### Scenario: Reader reads the management track
- **WHEN** a reader opens the management track
- **THEN** the levels appear in that order and the top level is M5 (CTO)

### Requirement: M1 is paired with IC4
Career skills SHALL show M1 as the management pair of IC4. The on-call roster SHALL say IC4 or M1 where it now says IC3 or EM3. It MUST NOT pair M1 with IC3, and it MUST NOT keep EM3.

#### Scenario: Reader checks who can be incident manager
- **WHEN** a reader opens the on-call roster
- **THEN** the incident manager rule and the on-call engineer rule say IC4 or M1

#### Scenario: Reader compares M1 with the IC levels
- **WHEN** a reader reads the career skills table
- **THEN** M1 is paired with IC4 and not with IC3

### Requirement: IC5 is not a copy of IC4
Career skills SHALL give IC5 a higher bar than IC4 on system design and on scope beyond one team. The two rows MUST NOT match in every column.

#### Scenario: Reader compares IC4 and IC5
- **WHEN** a reader reads the engineering skills table
- **THEN** IC5 differs from IC4 on system design and on scope, and the other columns are not a duplicate row
