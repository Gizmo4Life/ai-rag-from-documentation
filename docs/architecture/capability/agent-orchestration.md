---
id: agent-orchestration
type: capability
pillar: architecture
---
[Home](/) > [Architecture](/docs/architecture/readme.md) > [Capability](readme.md) > Agent Orchestration

# Capability: Agent Orchestration

Orchestrates the interaction between external AI agents and the repository's human-oriented documentation.

## 1. Description
Provides the interfaces, instructions, and workflows that allow AI systems to reason over the repository's rules and execute protocols autonomously.

## 2. Business Logic
- **Instruction Injection**: Providing persona and behavior rules via directive files.
- **Workflow Execution**: Mapping slash commands to multi-step protocols.
- **Context Retrieval**: Enabling RAG-optimized discovery of patterns and standards.

## 3. Composition
- [Agent Workflows](docs/architecture/module/agent-workflows.md)
- [AI Config](docs/architecture/module/ai-config.md)
