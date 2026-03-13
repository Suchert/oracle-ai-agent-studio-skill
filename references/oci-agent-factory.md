# OCI AI Database Private Agent Factory

This is a SEPARATE product from Oracle AI Agent Studio for Fusion Applications.
This reference clarifies the distinction.

## Key Difference

| Aspect | AI Agent Studio (Fusion) | AI Database Private Agent Factory (OCI) |
|--------|--------------------------|----------------------------------------|
| Platform | Oracle Fusion Cloud Apps | OCI (any Oracle Database) |
| Focus | Enterprise business processes | Database operations and analytics |
| Deployment | Embedded in Fusion | OCI Marketplace or on-premises |
| Agents | Pre-built for HCM/ERP/SCM/CX | Pre-built Data Analysis Agent + custom |
| Integration | Fusion APIs, tools, workflows | Database SQL, MCP, REST |
| Users | Business users, HR, Finance | DBAs, developers, data analysts |

## AI Database Private Agent Factory Overview

- Enterprise-ready, no/low-code approach to agent development
- Close to your data, compliant with governance, fast to deploy
- Deploy on-premises, multi-cloud, or via OCI Marketplace (one-click)
- Includes pre-built agents (e.g., Data Analysis Agent) and Agent Builder
- Agent Builder: Visual workflow editor with drag-and-drop components
- Supports custom MCP servers for extending agent capabilities
- Agents can be published to REST endpoints for use in custom applications

## When to Use Which

Use **AI Agent Studio (Fusion)** when:
- Working within Oracle Fusion Cloud Applications
- Building agents for HR, Finance, Supply Chain, or Service workflows
- Need native Fusion API access and security model
- Deploying through the Fusion AI Agent Marketplace

Use **AI Database Private Agent Factory** when:
- Working directly with Oracle Database (19c, 23ai, 26ai)
- Need agents for SQL querying, data analysis, database administration
- Want on-premises or multi-cloud deployment
- Building custom data-centric agent workflows

## Related Skills

For Oracle Database operations, use `krisrice/oracle-db-skills` which provides
100+ skills for SQL, PL/SQL, performance tuning, security, and more, designed
to work with MCP tools.
