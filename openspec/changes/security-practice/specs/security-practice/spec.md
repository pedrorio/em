# Spec Delta

## Purpose

States who owns security, what an RFC must show, and that a security incident is written up on the existing post-mortem.

## ADDED Requirements

### Requirement: Security template names the owner and the RFC check
`public/engineering/security.md` SHALL name the owner and SHALL state what an RFC must show before it is accepted. It SHALL point at the architecture document and at the RFC template. The readme SHALL link it as "Security".

#### Scenario: Reader checks an RFC for security
- **WHEN** a reader opens the security template during an RFC review
- **THEN** it names an owner, lists what the RFC must show, and points at the architecture document and the RFC template

### Requirement: Security incidents use the post-mortem
The security template SHALL send a security incident to the existing post-mortem. It MUST NOT define a second incident template.

#### Scenario: A security incident is closed
- **WHEN** a reader follows the incident path on the security template
- **THEN** it points at the post-mortem template and does not link a second incident write-up
