---
id: repository-use-cases
type: standard
pillar: external
---
[Home](/) > [Docs](/docs/readme.md) > [External](/docs/external/readme.md) > Use Cases

# Repository Use Cases

This repository is designed to serve two primary operational contexts. The choice of context determines the bias toward quality controls and the intended outcome of agent interactions.

## 1. Greenfield Bootstrap (Fork)
**Context:** Forking this repository to serve as the foundation for a new project.

- **Objective:** Build out new capabilities from scratch.
- **Bias:** Heavy bias towards 100% documentation coverage and strict protocol compliance.
- **Outcome:** A high-integrity, RAG-optimized codebase where every line of code is justified by a corresponding pattern or standard.

> [!TIP]
> Follow the [Greenfield Bootstrap Procedure](../developer/workflow/consumption-strategies.md#1-greenfield-bootstrap-forking) for technical setup steps.


## 2. Brownfield Discovery (Merge)
**Context:** Merging the contents of this repository (specifically the `docs/` and `.agent/` structures) into an existing project.

- **Objective:** Map existing codebases to identify gaps, architectural weaknesses, and areas for improvement.
- **Bias:** Focus on the **Discovery Protocol** and **Pattern Intake**.
- **Outcome:** A formalized "Knowledge Graph" of the existing system, enabling agents to reason about legacy code with the same precision as new code.

> [!TIP]
> Follow the [Brownfield Discovery Procedure](../developer/workflow/consumption-strategies.md#2-brownfield-discovery-merging) for technical integration steps.

