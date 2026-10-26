# Spec Delta

## Purpose

Turns the retrospective into a usable review that still has its three columns and can check open post-mortem actions.

## ADDED Requirements

### Requirement: Retrospective keeps its three columns and reviews actions
The retrospective template SHALL name the team and the date, SHALL keep Went well, To improve, and Action points, and SHALL include open post-mortem actions with the owner, due date, and status from the post-mortem.

#### Scenario: Team holds a retrospective
- **WHEN** a team fills in the retrospective
- **THEN** it records the team, the date, the three columns, and any open post-mortem actions
