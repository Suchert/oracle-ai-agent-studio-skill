# Feature Availability by Oracle Fusion Release

Plan your implementation based on your environment's version.

| Feature | Release | Notes |
|---------|---------|-------|
| AI Agent Studio (core) | 25A (Mar 2025) | Agent Designer, Tools, Agents, Agent Teams, testing |
| Pre-built agent templates | 25A | Initial set of HCM, ERP, SCM templates |
| Third-party LLM support | 25B (Oct 2025) | OpenAI, Anthropic, Cohere, Google, Meta, xAI |
| AI Agent Marketplace | 25B (Oct 2025) | Partner-built templates, certified by Oracle |
| MCP support | 25B (Oct 2025) | Model Context Protocol for external integrations |
| A2A support | 25B (Oct 2025) | Agent-to-Agent Protocol for cross-system collaboration |
| Workflow-type agents | 25B (Oct 2025) | Deterministic execution, chaining, branching |
| Human-in-the-loop | 25B (Oct 2025) | Approval gates in workflow agents |
| Agent tracing | 25B (Oct 2025) | Detailed execution debugging |
| Performance metrics | 25B (Oct 2025) | Correctness, latency, API errors, token consumption |
| Token usage tracking | 25B (Oct 2025) | Measure LLM token consumption for cost prediction |
| Prompt Library | 25C (2026) | Central prompt and topic management |
| Topics management | 25C (2026) | Centralized topic store across agents |
| Runtime file upload | 26A (2026) | Users upload attachments during agent chat |
| Third-party file upload | 26A (2026) | Upload from configured cloud storage providers |

## Runtime File Upload Details (26A)

Supported file types: PDF (tagged or scanned), TXT, DOCX, XLSX, PNG, JPEG
Limits: Up to 5 files per interaction, 50 MB total combined size
Requires: Runtime processing tool added to the agent or node
Third-party upload: Requires credentials configured in the Credentials tab

## Key Milestone Summary

- **25A**: Foundation — build and test agents with Oracle's default LLM (Cohere)
- **25B**: Enterprise — multi-provider LLMs, workflows, marketplace, MCP/A2A, observability
- **25C/26A**: Maturity — prompt lifecycle management, runtime attachments, expanded tooling

Always verify available features in your specific environment. Some features may
require specific OCI service configurations or additional enablement steps.
Contact Oracle Support if features expected for your release are not visible.
