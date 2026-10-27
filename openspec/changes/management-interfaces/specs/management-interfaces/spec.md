# Spec Delta

## Purpose

States how M1 and M2 work with ICs, how managers work with each other, and how Director, VPE, and CTO work with the managers below them.

## ADDED Requirements

### Requirement: Three management interfaces
`public/organisation/management_interfaces.md` SHALL describe how M1 and M2 work with ICs, how managers work with each other, and how M3 (Director), M4 (VPE), and M5 (CTO) work with the managers below them. The readme SHALL link it as "Management interfaces".

#### Scenario: Reader opens the interfaces
- **WHEN** a reader follows the Management interfaces link
- **THEN** the template has those three interfaces and uses the ladder's role names

### Requirement: Interfaces point at the 1:1 and feedback templates
Each interface SHALL point at the 1:1 template and the feedback template. It MUST NOT copy their sections.

#### Scenario: Reader needs the conversation format
- **WHEN** a reader is on an interface section
- **THEN** the section points at the 1:1 template and the feedback template
