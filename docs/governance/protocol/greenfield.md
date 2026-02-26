---
id: greenfield-protocol
type: protocol
pillar: governance
---
[Home](/) > [Docs](/docs/readme.md) > [Governance](/docs/governance/readme.md) > [Protocol](readme.md) > Greenfield

## 1. Objective
Add new functionality by deriving a testable solution definition, scaffolding the architecture, and executing the implementation.

## 2. Planning & Design
- **Action:** Execute [Test Planning](test-planning.md) to define acceptance criteria.
- **Action:** Execute [Architecture Review](architecture-review.md) to map the new functionality.
- **Action:** Execute [Standard Definition](standard-definition.md) to select appropriate patterns.
- **Action:** Execute [Operational Readiness](operational-readiness.md) to plan telemetry and recovery.
- **Verify:** User approval of the T2 Capability and test definition *before* proceeding.

## 3. Implementation Execution
- **Action:** Materialize the hollow [T3 Modules](/docs/developer/pattern/doc-t3-module.md) (Architecture).
- **Action:** Select the **Preferred (P)** [Patterns] from the [Standard] (Standard).
- **Action:** Write the physical code in `/src` adhering strictly to the selected Patterns.
- **Action:** Materialize required [Operational Artifacts] (Runbooks/Alerts).
- **Action:** Embed the [Signpost Readme] in the new directories.
- **Action:** Execute [Documentation Validation](documentation-validation.md) to ensure all artifacts are correctly formatted and linked.
- **Verify:** Execute the test/verification and final [Operational Readiness].