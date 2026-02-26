---
id: arch-documentation
type: standard
pillar: governance
---
[Home](/) > [Docs](/docs/readme.md) > [Governance](/docs/governance/readme.md) > [Standard](readme.md) > Architecture Documentation

## Context: System Design & Mapping
*Nuance: Architecture documentation must cleanly separate business intent from code mechanics. Mixing these creates fragile documentation that breaks on every code refactor.*

| Pattern | Rating | Contextual Nuance |
| :--- | :--- | :--- |
| [doc-t1-landscape](/docs/developer/pattern/doc-t1-landscape.md) | **P** | Required at the root of `docs/architecture/` |
| [doc-t2-capability](/docs/developer/pattern/doc-t2-capability.md) | **P** | Business logic focus. Implementation agnostic. |
| [doc-t3-module](/docs/developer/pattern/doc-t3-module.md) | **P** | Physical mapping. Must link to `/src`. |
| [doc-t2-with-code](/docs/developer/pattern/doc-t2-with-code.md) | **U** | Mixing code snippets in strategy files. |
| [doc-t3-with-biz-logic](/docs/developer/pattern/doc-t3-with-biz-logic.md) | **U** | Mixing intent in implementation maps. |