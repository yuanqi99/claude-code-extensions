# Claude Code 扩展集 (Claude Code Extensions)

[English](./README_EN.md)

本仓库致力于收集和分享 **Claude Code** 的优质扩展资源，包括 **Skill (技能)**、**Plugin (插件)** 以及各类配置指南，旨在提升 AI 在编程和项目管理中的持久化记忆与自动化能力。

## 资源列表

### 1. 记忆增强 (Memory Enhancement)

| 名称 | 类型 | 说明 | 状态 |
| :--- | :--- | :--- | :--- |
| [project-memory](./skills/project-memory/) | **Skill** | 基于 `MEMORY.md` 的轻量级、原生项目记忆管理。 | 稳定 |
| [claude-mem-guide](./plugins/claude-mem-guide/) | **Plugin** | 热门插件 `claude-mem` 的详细安装与使用指南（支持向量搜索）。 | 推荐 |

## 快速开始

### 什么是 Skill (技能)？
技能是给 Claude 的“操作手册”。它不需要安装，只需要将对应的文件夹放入项目的 `.claude/skills/` 目录中。Claude 会根据指令自动执行任务。

### 什么是 Plugin (插件)？
插件是更底层的扩展，通常需要通过 `/plugin install` 命令安装，并运行后台服务来实现自动化功能（如自动保存对话到数据库）。

## 如何使用本仓库

1. **克隆仓库**：
   ```bash
   git clone https://github.com/yuanqi99/claude-code-extensions.git
   ```
2. **选择你需要的扩展**：
   - 如果你想要简单的记忆管理，请查看 `skills/project-memory`。
   - 如果你想要强大的向量搜索记忆，请查看 `plugins/claude-mem-guide`。

## 贡献指南

欢迎提交 Pull Request 来分享你的 Claude Code 技能或插件指南！

## 开源协议

[MIT License](./LICENSE)
