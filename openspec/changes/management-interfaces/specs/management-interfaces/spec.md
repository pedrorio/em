# Spec Delta

## Purpose

States the working interface for an EM with ICs, for EMs with each other, and for a Senior EM with EMs and above.

## ADDED Requirements

### Requirement: Three management interfaces
`public/organisation/management-interfaces.md` SHALL describe how an EM works with ICs, how EMs work with each other, and how a Senior EM works with EMs and above. The readme SHALL link it as "Management interfaces".

#### Scenario: Reader opens the interfaces
- **WHEN** a reader follows the Management interfaces link
- **THEN** the template has those three interfaces and uses the ladder's role names

### Requirement: Interfaces point at the 1:1 and feedback templates
Each interface SHALL point at the 1:1 template and the feedback template. It MUST NOT copy their sections.

#### Scenario: Reader needs the conversation format
- **WHEN** a reader is on an interface section
- **THEN** the section points at the 1:1 template and the feedback template
