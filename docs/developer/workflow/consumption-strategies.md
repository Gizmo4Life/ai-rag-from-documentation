---
id: consumption-strategies
type: workflow
pillar: developer
tags: [bootstrap, integration, workflows]
---
[Home](/) > [Docs](/docs/readme.md) > [Developer](/docs/developer/readme.md) > [Workflow](readme.md) > Consumption Strategies

# Consumption Strategies

Technical procedures for utilizing this repository in different operational contexts.

## 1. Greenfield Bootstrap (Forking)
Use this procedure when starting a new project with this repository as the base.

### Procedure
1.  **Fork \& Clone:**
    ```bash
    # Using GitHub CLI
    gh repo fork Gizmo4Life/ai-rag-from-documentation --clone -- <project-name>

    # OR using standard Git
    git clone https://github.com/YOUR_USERNAME/ai-rag-from-documentation.git <project-name>
    cd <project-name>
    ```

2.  **Environment Setup:** Follow the [Getting Started](getting-started.md) guide to initialize the environment.

3.  **Baseline Verification:**
    - Run the [Discovery Protocol](../../governance/protocol/discovery.md) to ensure the baseline is clean.
    - Execute `npm run audit` to verify compliance.
4.  **Capability Development:**
    - Use the [Greenfield Protocol](../../governance/protocol/greenfield.md) for all new feature development.
    - Ensure every new module follows the [Standard Definition](../../governance/protocol/standard-definition.md).

## 2. Brownfield Discovery (Merging)
Use this procedure when integrating the repository's governance and agent framework into an existing project.

### Procedure
1.  **Integrate Structure:**
    - Copy the `docs/`, `.agent/`, and `.github/copilot-instructions.md` into your existing project root.
2.  **Initialize Patterns:**
    - Perform a repository-wide [Discovery](../../governance/protocol/discovery.md).
    - Identify core architectural shapes and ingest them using the [Pattern Intake](../../governance/protocol/pattern-intake.md) protocol.
3.  **Gap Analysis:**
    - Create [Architecture Reviews](../../governance/protocol/architecture-review.md) for existing modules to identify drift from modern standards.
4.  **Iterative Alignment:**
    - Gradually bring existing code into compliance by wrapping legacy logic in new, atomic patterns.
