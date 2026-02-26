# Repository Architect Directives

## 1. Governance Routing
Every interaction must adhere to the [Governance Pillar](../docs/governance/readme.md). Consult the [Agent Manifest](../docs/governance/agent-manifest.md) to choose the appropriate protocol for the current context.

## 2. Structural Purity
- **Atomicity**: Patterns = "What", Standards = "Should". extract inlined patterns.
- **One-Deep Rule**: Maintain singular directory depth. No nested subfolders.
- **Readability**: README paragraphs must not exceed 2 sentences.

## 3. Mandatory Verification
No change is complete without executing the relevant modular sub-protocols defined in the [Governance Pillar](../docs/governance/readme.md) or [Pillar Manifests](../docs/readme.md).


## 4. RAG Optimization
Ensure every `.md` file has YAML frontmatter. Manifests must conclude with an `index_map` YAML block for automated traversal.