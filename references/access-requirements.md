# Access Requirements for Oracle AI Agent Studio

## Prerequisites

Before using AI Agent Studio, ensure the following:

1. **Oracle Fusion Cloud Applications environment**: Release 25A or later for full Agent Studio capabilities
2. **OCI services deployed**: Your environment must have Oracle Applications Platform services deployed (see FAQ2521 on My Oracle Cloud Support)
3. **Profile option enabled**: Set `ORA_ASE_SAS_INTEGRATION_ENABLED` to `Yes` in Setup and Maintenance
4. **Permission groups**: Enable permission groups for the appropriate roles

## Required Roles

Access to AI Agent Studio and its components is role-based:

- **AI Studio Administrator**: Full access — can create, edit, publish, and manage all agents, tools, and teams. Can also grant access to other users.
- **AI Studio Developer**: Can create and edit agents, tools, and teams within granted scope
- **AI Studio Viewer**: Read-only access to agent configurations and evaluation results

The agents visible to each user depend on the roles and privileges assigned to them.
To access specific agent templates (e.g., Skill Recommendation Agent), your role
must be explicitly granted access by an AI Studio Administrator.

## Enabling Access

1. Navigate to **Setup and Maintenance**
2. Search for and enable `ORA_ASE_SAS_INTEGRATION_ENABLED` profile option → set to `Yes`
3. Configure permission groups for the roles that need Agent Studio access
4. Assign the appropriate AI Studio role to each user

## AI Agent Marketplace Access

To access the Oracle AI Agent Marketplace (third-party agents from certified partners):
- Must have AI Studio Administrator or Developer role
- Partner agents appear alongside Oracle pre-built agents in a unified experience
- Agents from the Marketplace can be installed, tested, and deployed within existing workflows

## Certification

Oracle offers training and certification for AI Agent Studio:
- **Oracle Fusion AI Agent Studio Foundations Associate**
- Available at: https://mylearn.oracle.com/ou/learning-path/oracle-fusion-ai-agent-studio-foundations-associate/151552
- Over 32,000 experts have been certified as of October 2025
