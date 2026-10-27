# Spec Delta

## Purpose

Gives the architecture document, the product rungs, and new template files one name each so later changes do not invent a second name.

## ADDED Requirements

### Requirement: Architecture document has one name
Discovery notes and the engineering group template SHALL call the C4 document the architecture document. They MUST NOT call that file ADR or ARD.

#### Scenario: Reader looks up the system document
- **WHEN** a reader opens the discovery note or the engineering group ownership table
- **THEN** the system document is named architecture document, and ADR and ARD are not used for it

### Requirement: Product rungs are named once
The discovery note SHALL name three rungs in order: market (`mrd`), business model (`business_case`), and feature (`prd`).

#### Scenario: Reader follows discovery
- **WHEN** a reader reads the market and product sections of the discovery note
- **THEN** the market rung points at `mrd`, the business-model rung points at `business_case`, and the feature rung points at `prd`

### Requirement: Template file names are snake_case
A public template file name MUST be snake_case. Each existing hyphenated public template MUST be renamed to snake_case, and the readme link MUST follow. This rename MUST NOT change the file body. A short acronym with no extra word stays lowercase, as `mrd.md` and `rfc.md`. The market file MUST be `public/product/mrd.md`.

#### Scenario: Reader opens a renamed template
- **WHEN** a reader follows the architecture document, career ladder, career skills, engineering group, program increment, or post-mortem link in the readme
- **THEN** the target file name uses underscores and contains no hyphen

#### Scenario: Market file is linked from the readme
- **WHEN** a reader follows the market requirements link in the readme
- **THEN** the target is `public/product/mrd.md`

### Requirement: Architectural Review stays a meeting name
The program increment template MUST keep the name Architectural Review for that meeting.

#### Scenario: Quarterly context is read
- **WHEN** a reader opens the program increment context
- **THEN** Architectural Review is still listed, and it is not renamed to architecture document
