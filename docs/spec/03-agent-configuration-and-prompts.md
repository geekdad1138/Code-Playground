# Specification: Agent Configuration & Prompts

## 1. Overview
This specification details how the "Code Playground" repository will document the configuration, tuning, and orchestration of AI agents (like GitHub Copilot) within the IDE environment.

## 2. Configuration Layers to Document
The repository will break down the `Kitchen Equipment` of AI development into standard layers:

### A. Global Instructions (`.github/copilot-instructions.md`)
- **Purpose:** Broad rules for how the AI should behave across the entire project (e.g., tone, preferred syntax, documentation standards).
- **Educational Content:** Examples of effective global instructions and explanations of *why* certain rules are necessary.

### B. Custom Prompts (`.github/prompts/`)
- **Purpose:** Reusable, specific markdown files that can be invoked via slash commands in Copilot chat.
- **Educational Content:** A library of custom prompts for common workflows (e.g., `/refactor-solid`, `/generate-tests`, `/audit-security`).

### C. The `agents.md` File
- **Purpose:** Defining multi-agent systems, sub-agent roles, and orchestration loops.
- **Educational Content:** 
  - How to define distinct personas (e.g., "The Python Developer", "The QA Engineer").
  - Explaining the sequential nature of sub-agents and how to pass outputs from one to another.
  - Demonstrating context pinning to limit an agent's view to specific files.

## 3. Demonstration Methodology
To share knowledge:
1. **Prompt the Prompt:** The user will ask the AI to generate config files for a dummy scenario (e.g., "Write an `agents.md` for a .NET Core 9 project").
2. **Document the Output:** The verbatim output will be saved in the `examples/` directory.
3. **Annotate:** The repository will include commentary explaining the components of the generated file to aid community learning.

## 4. Context Isolation via Profiles
The documentation will also cover how to build VS Code Profiles (e.g., a "Python Agent Profile" vs. a ".NET Agent Profile") to rigidly separate context, extensions, and agent behaviors between different projects running in the same IDE.
