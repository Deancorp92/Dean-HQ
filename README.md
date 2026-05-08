# Dean HQ

Dean HQ is the control repository for a company-style AI operating system.

## Purpose
- Manage Dean, the central orchestrator agent.
- Organize department agents.
- Keep approval rules, report templates, and archives in one place.

## Core Structure
- `agents/` : agent definitions
- `policies/` : approval and safety rules
- `docs/` : report templates and logs
- `archive/` : legacy formats and retired documents
- `.github/workflows/` : automation workflows

## Operating Principle
- Dean receives requests.
- Dean routes work to the right department.
- Dean summarizes results in a short report.
- The user approves important decisions.
- Legacy formats are archived, not deleted.

## First Agents
- Dean
- Management Agent
- Business Development Agent
- Product Development Agent
