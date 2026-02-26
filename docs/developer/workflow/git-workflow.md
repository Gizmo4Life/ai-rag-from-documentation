---
id: git-workflow
type: workflow
pillar: developer
---
[Home](/) > [Docs](/docs/readme.md) > [Developer](/docs/developer/readme.md) > [Workflow](readme.md) > Git Workflow

# Git Workflow: Trunk-Based Development

We use a Trunk-Based Development (TBD) strategy to ensure rapid integration and high code quality.

## 1. Branching Strategy
- **Trunk (`main`):** The single source of truth. Always deployable.
- **Short-Lived Branches:** Developers create branches from `main` for specific features or fixes.
  - *Naming:* `feat/...`, `fix/...`, or `task/...` followed by a descriptive slug.
  - *Lifecycle:* Branches should exist for no more than 2-3 days before merging.

## 2. Pull Request (PR) Process
Every change to the trunk must go through a Pull Request.

1.  **Preparation:**
    - Ensure your code is formatted and passes local linting.
    - Run the relevant test suite for your changes.
2.  **Documentation (DaC):**
    - Every PR must include a `walkthrough.md` artifact (pattern: [Restoration Step](/docs/developer/pattern/doc-ops-restoration-step.md)).
    - If new patterns or standards are introduced, they must be materialized in `docs/`.
3.  **Creation:**
    - Provide a concise title and a detailed description of the "Why."
    - Link to any relevant T2 Capabilities or T3 Modules.
4.  **Review:** 
    - At least one approval is required from a peer or lead.
    - Reviewers follow the [PR Review](/docs/governance/protocol/pull-request-review.md) protocol.

## 3. Quality Gates
Before a PR is merged into `main`, it must pass:

- **Automated Validation:** CI checks for build success, linting, and unit tests (adhering to [CI/CD Pipeline](/docs/governance/standard/cicd-pipeline.md) standards).
- **Architectural Check:** Verification that the code matches the [Preferred (P)](/docs/developer/pattern/padu-evaluation.md) patterns in the standards.
- **Integrity Check:** Execute the [Documentation Validation](/docs/governance/protocol/documentation-validation.md) protocol to ensure no drift or broken links were introduced.

## 4. Merging
- Once approved and CI passes, use **Squash and Merge** to keep a clean history.
- Delete the feature branch immediately after merging.
