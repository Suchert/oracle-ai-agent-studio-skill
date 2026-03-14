# Cross-Tenancy IAM Policies for Agent Tools

When an agent tool references an agent endpoint in a different OCI tenancy,
cross-tenancy IAM policies are required.

## When This Applies

- Your Agent tool is in Tenancy A
- The agent endpoint it invokes is in Tenancy B (the "target tenancy")
- Both tenancies need explicit IAM policy statements

## Required Information

Gather before writing policies:
- Target tenancy name and OCID (where the agent endpoint lives)
- Source tenancy name and OCID (where you're creating the Agent tool)
- Dynamic group name and OCID

## Policy Statements

### In the source tenancy (where the Agent tool is created)

```
Define tenancy <target-tenancy> as <target-tenancy-ocid>

Endorse dynamic-group <dynamic-group-name> to use genai-agent-endpoints in tenancy <target-tenancy>
```

> **Least-privilege note**: Use `use genai-agent-endpoints` (read + invoke) rather than
> `manage genai-agent-family` (full CRUD + delete). Grant `manage` only when the source
> service must create or update agent resources in the target tenancy.

### In the target tenancy (where the agent endpoint lives)

```
Admit dynamic-group <dynamic-group-name> of tenancy <source-tenancy> to use genai-agent-endpoints in tenancy
```

## Identity Domain Considerations

If using an identity domain that is NOT the Default domain, use the form:

```
<idcs-domain-name>/<dynamic-group-name>
```

in place of just `<dynamic-group-name>` in all policy statements.

## General Agent Access Policies

Regardless of cross-tenancy setup, ensure all users have access to
Generative AI Agents resources as described in the OCI documentation
for "Adding Policies Before You Can Use the Service."

## Multi-Agent Supervisor Setup

For supervisor agents that orchestrate collaborator agents:

1. Configure IAM policies for all involved tenancies
2. Create collaborator agents with any tool type
3. Ensure each collaborator has an active, session-enabled agent endpoint
4. Create the supervisor agent and add collaborators using the Agent tool type
5. Ensure the supervisor's agent endpoint is also session-enabled
