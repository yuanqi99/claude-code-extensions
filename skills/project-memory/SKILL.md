# Project Memory Skill

Maintain a persistent project memory using `MEMORY.md` to track decisions, patterns, and context across sessions.

## Activation
This skill activates when:
- The user mentions "remember this", "save to memory", or "update project context".
- A session ends and there are significant learnings to capture.
- A new session starts and context needs to be reloaded.

## Instructions

### 1. Memory Structure
Always use or create a `MEMORY.md` file in the project root with the following sections:
- **Project Overview**: High-level purpose and goals.
- **Tech Stack**: Languages, frameworks, and key libraries.
- **Conventions**: Coding style, naming conventions, and architectural patterns.
- **Decisions**: Log of significant technical decisions and their rationale.
- **Lessons Learned**: Common mistakes to avoid or complex logic explanations.

### 2. Updating Memory
- **Evidence Threshold**: Only add patterns observed in 2+ sessions or explicitly requested by the user.
- **Conciseness**: Keep entries brief and actionable.
- **Cleanup**: Remove outdated or contradicted information.

### 3. Usage Pattern
- At the start of a session, read `MEMORY.md` to align with project state.
- During the session, if a new pattern emerges, note it for a memory update.
- Before closing, propose updates to the user using the `AskUserQuestion` tool (if available) or via clear confirmation.
