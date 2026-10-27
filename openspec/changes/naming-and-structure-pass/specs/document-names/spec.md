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
The discovery note SHALL name three rungs in order: market (`mrd`), business model (`brd`), and feature (`prd`).

#### Scenario: Reader follows discovery
- **WHEN** a reader reads the market and product sections of the discovery note
- **THEN** the market rung points at `mrd`, the business-model rung points at `brd`, and the feature rung points at `prd`

### Requirement: New template file names
A new public template MUST use a snake_case file name. An existing file name MUST stay as it is. A short acronym with no extra word stays lowercase, as `mrd.md` and `rfc.md`. The market file MUST be `public/product/mrd.md`, and the readme link target MUST match that path.

#### Scenario: A new multi-word template is added
- **WHEN** a later change adds a template whose name has more than one word
- **THEN** the file name uses underscores and does not use hyphens

#### Scenario: Market file is linked from the readme
- **WHEN** a reader follows the market requirements link in the readme
- **THEN** the target is `public/product/mrd.md`

### Requirement: Architectural Review stays a meeting name
The program increment template MUST keep the name Architectural Review for that meeting.

#### Scenario: Quarterly context is read
- **WHEN** a reader opens the program increment context
- **THEN** Architectural Review is still listed, and it is not renamed to architecture document
