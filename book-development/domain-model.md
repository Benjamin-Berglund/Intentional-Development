# Domain Model

This document defines the core conceptual vocabulary of the book.

## Core concepts

```text
Intent
│
├── Shared Understanding
│   ├── Language
│   ├── Domain Models
│   ├── Graphs
│   ├── Wireframes
│   └── Examples
│
├── Behavior
│   ├── Scenarios
│   ├── BDD
│   ├── Acceptance Criteria
│   └── Executable Specifications
│
├── Verification
│   ├── Testing
│   ├── Review
│   ├── Observability
│   ├── Metrics
│   └── Evidence
│
├── Drift
│   ├── Specification Drift
│   ├── Cognitive Drift
│   ├── Behavioral Drift
│   ├── Operational Drift
│   └── Organizational Drift
│
├── Delivery
│   ├── DevOps
│   ├── CI/CD
│   ├── Deployment
│   └── Feedback
│
└── Operating Models
    ├── Agile V
    ├── Feature-by-Feature Development
    └── AI-Assisted Development
```

## Intent

Intent is the imagined purpose, behavior, value, and meaning of the software before and during its construction.

Intent is not only what stakeholders say they want. It includes assumptions, domain knowledge, user needs, operational expectations, risks, constraints, and quality expectations.

## Specification drift

Specification drift is the gradual divergence between intended behavior and expressed, implemented, tested, or deployed behavior.

It can appear during:

- Domain discussion
- Requirements writing
- Design
- Implementation
- Testing
- Deployment
- Operation
- AI-assisted generation

## Shared understanding

Shared understanding is the temporary alignment of mental models between people involved in the work.

It is never complete and never permanent. It must be actively maintained through conversation, models, examples, verification, and feedback.

## Behavior

Behavior is the observable response of a system in a context.

Behavior is the most important bridge between human intent and technical implementation because it can be described, discussed, tested, and observed.

## Verification

Verification is the production of evidence that intent has been preserved.

Testing is one form of verification. Review, observability, monitoring, user feedback, auditability, and parity comparison are also forms of verification.

## Agile V

Agile V is a lightweight collaboration model that connects intent-forming activities on the left side with evidence-producing activities on the right side.

It is not a waterfall process. It is a cognitive mirror:

```text
What do we believe we are building?
↔
How do we know we built it?
```
