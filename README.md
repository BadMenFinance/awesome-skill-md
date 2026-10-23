# Awesome SKILL.md [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of SKILL.md skills, tools, and resources for AI coding agents.

[SKILL.md](https://www.agensi.io/learn/what-is-skill-md) is the open standard for teaching AI coding agents new capabilities. A SKILL.md file tells agents like Claude Code, Codex CLI, Cursor, Gemini CLI, and OpenClaw how to handle specific tasks — code review, testing, documentation, DevOps, and more. Drop a skill into your agent's skills folder and it works immediately.

This list covers the best skills, resources, and tools across the ecosystem.

## Contents

- [Skills by Category](#skills-by-category)
  - [Code Review](#code-review)
  - [Testing & QA](#testing--qa)
  - [DevOps & Deployment](#devops--deployment)
  - [Frontend & Design](#frontend--design)
  - [Documentation](#documentation)
  - [Git Automation](#git-automation)
  - [Productivity](#productivity)
  - [Data Engineering](#data-engineering)
  - [API Development](#api-development)
  - [Security](#security)
- [Marketplaces](#marketplaces)
- [Guides & Tutorials](#guides--tutorials)
- [Format & Reference](#format--reference)
- [Tools](#tools)
- [Compatible Agents](#compatible-agents)
- [Contributing](#contributing)

## Skills by Category

### Code Review

- [code-reviewer](https://www.agensi.io/skills/code-reviewer) — Structured code review for bugs, security vulnerabilities, logic errors, and style violations. Organizes findings by severity. Free.
- [security-audit](https://www.agensi.io/skills/security-audit) — Scans code for OWASP Top 10 vulnerabilities, hardcoded secrets, and authentication bypasses.

### Testing & QA

- [Best Testing & QA Skills for Claude Code](https://www.agensi.io/learn/best-claude-code-testing-skills) — Roundup of the top testing skills with comparisons.
- Skills for unit testing, integration testing, E2E testing, and coverage analysis on [Agensi Testing & QA](https://www.agensi.io/skills/testing-qa).

### DevOps & Deployment

- [env-doctor](https://www.agensi.io/skills/env-doctor) — Diagnoses why your project won't start. Checks runtime versions, dependencies, environment variables, database connections, and port conflicts. Free.
- [Best DevOps Skills for Claude Code](https://www.agensi.io/learn/best-claude-code-devops-skills) — Roundup of DevOps and deployment skills.
- More DevOps skills on [Agensi DevOps & Deployment](https://www.agensi.io/skills/devops-deployment).

### Frontend & Design

- [frontend-design](https://www.agensi.io/skills/frontend-design) — Component generation, CSS styling, accessibility checks, and design system workflows.
- [Best Frontend Skills for Claude Code](https://www.agensi.io/learn/best-claude-code-frontend-skills) — Roundup of frontend development skills.

### Documentation

- [readme-generator](https://www.agensi.io/skills/readme-generator) — Scans your project and generates a complete README with installation, usage, configuration, and contributing sections. Free.
- More documentation skills on [Agensi Documentation](https://www.agensi.io/skills/documentation).

### Git Automation

- [git-commit-writer](https://www.agensi.io/skills/git-commit-writer) — Writes conventional commit messages from staged changes. Detects type, scope, and breaking changes. Free.
- [pr-description-writer](https://www.agensi.io/skills/pr-description-writer) — Writes pull request descriptions from branch diffs. Covers what changed, why, and what to test. Free.
- [changelog-generator](https://www.agensi.io/skills/changelog-generator) — Generates changelogs from commit history following Keep a Changelog format.

### Productivity

- [skill-router](https://www.agensi.io/skills/skill-router) — Routes tasks to the right skill automatically based on context.
- [syncbook](https://github.com/theguysaccount/syncbook-agent) — Prepare a human-approved collaboration profile and find reciprocal collaborators through Syncbook. Free.
- More productivity skills on [Agensi Productivity](https://www.agensi.io/skills/productivity).

### Data Engineering

- Skills for databases, data pipelines, ETL, SQL optimization, and data modeling on [Agensi Data Engineering](https://www.agensi.io/skills/data-engineering).

### API Development

- [api-contract-tester](https://www.agensi.io/skills/api-contract-tester) — Tests API endpoints against their OpenAPI/Swagger specs.
- More API skills on [Agensi API Development](https://www.agensi.io/skills/api-development).

### Security

- [security-audit](https://www.agensi.io/skills/security-audit) — OWASP Top 10 scanning, secret detection, and authentication review.
- [dependency-auditor](https://www.agensi.io/skills/dependency-auditor) — Checks dependencies for known vulnerabilities.

## Marketplaces

- [Agensi](https://www.agensi.io) — Curated marketplace for SKILL.md skills. One-time purchase, security-scanned, 80/20 creator revenue split. Supports Claude Code, Codex CLI, Cursor, and 20+ agents.

## Guides & Tutorials

### Getting Started

- [What Is SKILL.md?](https://www.agensi.io/learn/what-is-skill-md) — Complete beginner's guide to the SKILL.md standard.
- [How to Install Skills in Claude Code](https://www.agensi.io/learn/how-to-install-skills-claude-code) — Three installation methods with step-by-step instructions.
- [Where Are Claude Skills Stored?](https://www.agensi.io/learn/where-are-claude-skills-stored) — File paths for Claude Code, OpenClaw, Codex CLI, and Cursor.

### Installation

- [How to Install Claude Skills from GitHub](https://www.agensi.io/learn/how-to-install-claude-skills-from-github) — Clone, verify, and troubleshoot GitHub-hosted skills.
- [How to Add Skills to Claude Code CLI](https://www.agensi.io/learn/how-to-add-skills-claude-code-cli) — Command-line installation guide.
- [Claude Code Skills Folder Location & Setup](https://www.agensi.io/learn/claude-code-skills-folder-location-setup) — Directory structure and organization.

### Creating Skills

- [How to Create a SKILL.md from Scratch](https://www.agensi.io/learn/create-skill-md-from-scratch) — Step-by-step tutorial for building your own skill.
- [How to Write a SKILL.md Description That Triggers](https://www.agensi.io/learn/write-skill-md-description-that-triggers) — Writing descriptions that reliably activate your skill.
- [SKILL.md Examples](https://www.agensi.io/learn/skill-md-examples) — Copy-paste examples for common skill types.

### Comparisons

- [Claude Code Skills vs Cursor Rules vs Codex Skills](https://www.agensi.io/learn/claude-code-skills-vs-cursor-rules-vs-codex-skills) — Side-by-side comparison of format, portability, and ecosystem.
- [SKILL.md vs CLAUDE.md vs .cursorrules](https://www.agensi.io/learn/skill-md-vs-claude-md-vs-cursorrules) — When to use each configuration file.

## Format & Reference

- [SKILL.md Format Reference](https://www.agensi.io/learn/skill-md-format-reference) — Complete specification of frontmatter fields, triggers, and file structure.

### Minimal SKILL.md Template

```markdown
---
name: my-skill
description: One sentence describing when this skill should activate.
---

# Skill Title

Instructions for the AI agent go here. Write them like you're
briefing a senior developer.

## Rules
- Rule 1
- Rule 2

## Output Format
Describe how the agent should structure its output.
```

### Directory Structure

```
~/.claude/skills/
├── code-reviewer/
│   └── SKILL.md
├── test-generator/
│   └── SKILL.md
└── env-doctor/
    ├── SKILL.md
    └── references/
        └── common-issues.md
```

## Tools

- [Agensi AI Search](https://www.agensi.io/search) — Describe what you need and find matching skills.
- [Agensi MCP Server](https://mcp.agensi.io) — Connect your agent to the full skill catalog via MCP. Skills are loaded on demand.
- [Agensi Skill Request Board](https://www.agensi.io/requests) — Request skills that don't exist yet. Creators build to community demand.

## Compatible Agents

SKILL.md works across these AI coding agents:

| Agent | Personal Skills Path | Project Skills Path |
|-------|---------------------|-------------------|
| [Claude Code](https://docs.anthropic.com/en/docs/claude-code) | `~/.claude/skills/` | `.claude/skills/` |
| [Codex CLI](https://github.com/openai/codex) | `~/.codex/skills/` | `.codex/skills/` |
| [OpenClaw](https://openclaw.ai) | `~/.openclaw/skills/` | `.openclaw/skills/` |
| [Cursor](https://cursor.com) | — | `.cursor/skills/` |
| [Gemini CLI](https://github.com/google-gemini/gemini-cli) | `~/.gemini/skills/` | `.gemini/skills/` |

And 15+ more agents that support the SKILL.md standard.

## Contributing

Contributions welcome! Please read the [contributing guidelines](CONTRIBUTING.md) before submitting a pull request.

### How to Add a Skill

1. Make sure the skill uses the SKILL.md format
2. Add it under the appropriate category
3. Include: name, link, one-line description, and whether it's free or paid
4. Submit a pull request

### How to Add a Resource

1. Add it under the appropriate section
2. Include: title, link, and one-line description
3. Submit a pull request

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
