---
id: architecture-review
type: protocol
pillar: governance
---
[Home](/) > [Docs](/docs/readme.md) > [Governance](/docs/governance/readme.md) > [Protocol](readme.md) > Architecture Review

## 1. Objective
Ensure structural alignment with the repository's T1 (Landscape), T2 (Capability), and T3 (Module) hierarchy.

## 2. Structural Alignment
- **Verify:** The new code/doc belongs to an existing [T2 Capability].
- **Verify:** The new files are mapped to a [T3 Module].
- **Action:** If no mapping exists, execute [Discovery Protocol](discovery.md) to define new architectural artifacts.

## 3. Domain Integrity
- **Verify:** The new structure does not violate the singular pillar ownership rules.
- **Verify:** Dependencies between [T3 Modules] are explicitly documented.
- **Action:** If structural drift is detected, update the corresponding Landscape or Capability artifact.
