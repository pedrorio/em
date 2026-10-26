# Spec Delta

## Purpose

Makes every post-mortem action checkable later by giving it an owner, a due date, and a status.

## ADDED Requirements

### Requirement: Each post-mortem action is checkable
Each action item in the post-mortem template SHALL have an owner, a due date, and a status. The template MUST NOT add a second incident write-up.

#### Scenario: Owner reviews an action
- **WHEN** a reader looks at an action item on the post-mortem
- **THEN** the item shows an owner, a due date, and a status
