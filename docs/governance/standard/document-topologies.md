---
id: document-topologies
type: standard
pillar: governance
---
[Home](/) > [Docs](/docs/readme.md) > [Governance](/docs/governance/readme.md) > [Standard](readme.md) > Document Topologies

## Context: Repository Knowledge Graph
*Nuance: To support RAG and Agent Context Windows, documentation must be strictly typed, atomic, and heavily cross-linked.*

| Pattern | Rating | Contextual Nuance (Constraints & Limits) |
| :--- | :--- | :--- |
| [doc-t2-capability](/docs/developer/pattern/doc-t2-capability.md) | **P** | No implementation details. |
| [doc-t3-module](/docs/developer/pattern/doc-t3-module.md) | **P** | Physical-to-Pattern maps. Max 50 lines. |
| [doc-ops-restoration-step](/docs/developer/pattern/doc-ops-restoration-step.md) | **P** | Idempotent CLI tasks. Max 50 lines. |
| [doc-gov-protocol](/docs/developer/pattern/doc-gov-protocol.md) | **P** | System modification rules. |
| [doc-monolithic-wiki](/docs/developer/pattern/doc-monolithic-wiki.md) | **U** | Mixing orchestration with implementation. |
| [doc-narrative-paragraphs](/docs/developer/pattern/doc-narrative-paragraphs.md) | **U** | Exceeding 2 sentences per paragraph. |