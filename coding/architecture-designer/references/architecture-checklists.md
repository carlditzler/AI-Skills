# Architecture Checklists

## Boundaries
- What owns state?
- What causes side effects?
- What is synchronous vs asynchronous?
- What crosses process or thread boundaries?
- What is a stable contract vs internal detail?

## Simplicity
- Can a new feature be added without touching many layers?
- Is this abstraction solving a present problem?
- Are names specific enough that the next engineer will know where to edit?

## Reliability
- Is error handling explicit?
- Is cancellation or lifecycle behavior defined?
- Can core logic be tested without UI and without network?
