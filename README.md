# Oracle AI Agent Studio — Agent Skill

A cross-platform Agent Skill for working with Oracle AI Agent Studio in Oracle Fusion
Cloud Applications. Covers agent creation, configuration, deployment, testing,
monitoring, and integration with Fusion workflows.

## What This Skill Covers

- Architecture and components of Oracle AI Agent Studio
- Step-by-step agent creation (Tools → Agents → Agent Teams → Test → Publish)
- Integration into Fusion Service, HCM, ERP, and SCM workflows
- Workflow patterns: deterministic, chaining, agent nodes, human-in-the-loop
- LLM configuration (Oracle, OpenAI, Anthropic, Google, Meta, Cohere, xAI)
- Monitoring, evaluation, observability, and agent tracing
- 70+ pre-built agent templates catalog
- MCP integration for third-party systems
- Security model and cross-tenancy IAM policies
- Profile options and scheduled processes configuration

## Installation

### Claude Code
```bash
# Copy to user-level skills
cp -r oracle-ai-agent-studio/ ~/.claude/skills/

# Or project-level
cp -r oracle-ai-agent-studio/ .claude/skills/
```

### Cursor
```bash
cp -r oracle-ai-agent-studio/ .cursor/skills/
```

### OpenAI Codex CLI
```bash
cp -r oracle-ai-agent-studio/ .agents/skills/
```

### VS Code (GitHub Copilot)
```bash
cp -r oracle-ai-agent-studio/ .github/skills/
```

### Windsurf
```bash
cp -r oracle-ai-agent-studio/ .windsurf/skills/
```

### Universal (via symlink)
```bash
cp -r oracle-ai-agent-studio/ ~/.agents/skills/
```

## Structure

```
oracle-ai-agent-studio/
├── SKILL.md                              # Main skill instructions
├── README.md                             # This file
├── references/
│   ├── prebuilt-agents-catalog.md        # 70+ pre-built agents by business function
│   ├── access-requirements.md            # Roles, permissions, prerequisites
│   ├── cross-tenancy-policies.md         # IAM policies for cross-tenancy agents
│   ├── security-considerations.md        # Prompt injection, credentials, GDPR, IAM
│   ├── oci-agent-factory.md              # Distinction: Fusion Studio vs OCI Factory
│   ├── official-docs-links.md            # Links to Oracle documentation
│   └── release-availability.md           # Feature-by-release matrix (25A/25B/25C/26A)
└── evals/
    └── evals.json                        # Test cases for skill validation
```

## Related Skills

- [oracle-db-skills](https://github.com/krisrice/oracle-db-skills) — 100+ Oracle Database skills
- [oracle/mcp](https://github.com/oracle/mcp) — MCP servers for Oracle products

## License

Apache 2.0

## Author

Created for use with Oracle Fusion Cloud Applications consulting work.
Contributions and improvements welcome.
