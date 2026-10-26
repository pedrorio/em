# Spec Delta

## Purpose

Records a hiring decision against a ladder level and hands the result to the onboarding expectations that already exist.

## ADDED Requirements

### Requirement: Hiring template has scorecard, plan, and debrief
`public/people/hiring.md` SHALL contain a scorecard, an interview plan, and a debrief. The readme SHALL link it as "Hiring".

#### Scenario: Reader opens hiring from the index
- **WHEN** a reader follows the Hiring link in the readme
- **THEN** the template shows a scorecard, an interview plan, and a debrief

### Requirement: Scorecard cites a ladder level
The scorecard SHALL name one ladder level and SHALL record a hire or no-hire decision with the evidence for it. It MUST NOT use Untrained, Basic, Intermediate, or Advanced as the decision.

#### Scenario: Interviewer scores a candidate
- **WHEN** an interviewer completes the scorecard
- **THEN** the scorecard names the ladder level and states hire or no-hire, and it does not use the four-point skill scale

### Requirement: Debrief feeds 7, 21, and 63 day expectations
The debrief SHALL state what the new hire must know by day 7, day 21, and day 63, and SHALL point at the onboarding list in the engineering group template.

#### Scenario: A hire is accepted
- **WHEN** the debrief is filled for a hire
- **THEN** it sets expectations for day 7, day 21, and day 63 and points at the existing onboarding list
