# Claude Code Extensions

[中文说明](./README.md)

A collection of high-quality extensions for **Claude Code**, including **Skills**, **Plugins**, and configuration guides, aimed at enhancing AI persistence and automation.

## Resources

### 1. Memory Enhancement

| Name | Type | Description | Status |
| :--- | :--- | :--- | :--- |
| [project-memory](./skills/project-memory/) | **Skill** | Lightweight, native project memory management using `MEMORY.md`. | Stable |
| [claude-mem-guide](./plugins/claude-mem-guide/) | **Plugin** | Detailed guide for the popular `claude-mem` plugin (vector search). | Recommended |

## Getting Started

### What is a Skill?
A Skill is a "manual" for Claude. It doesn't require installation; simply place the folder into your project's `.claude/skills/` directory.

### What is a Plugin?
A Plugin is a deeper extension that usually requires installation via `/plugin install` and runs background services for automation.

## License
[MIT License](./LICENSE)
