# Lumant Agency OS

This repository is the **operating system** of the Lumant AI Marketing Agency.

It contains the agency's knowledge base, agent roles, playbooks, lessons learned, and project management structure.

## Repository Structure

```
/agents/          — Agent roles, skills, playbooks, and lessons
/projects/        — Client project journals and documentation
/agency/          — Agency constitution, workflow, and operating model
```

## The Agency Team

| # | Agent | Role |
|---|-------|------|
| 01 | Agency Director | Orchestration, documentation, coordination |
| 02 | Strategist | Marketing, brand, and competitive strategy |
| 03 | Creative | Visual production, photography, design |
| 04 | Copywriter | Language, tone of voice, written content |
| 05 | Analyst | Measurement, performance, internal challenge |

## Operating Model

```
User → Agency Director → Specialist Team → Internal Challenge → Agency Director → User
```

- **GitHub** = organizational knowledge, project state, skills, decisions, history
- **File server** = production assets and large files
- **Day** = human review and direction
- **Night** = autonomous AI production

## Key Principles

1. GitHub is the single source of truth
2. All agents load their knowledge files before working on any project
3. No draft is automatically approved
4. The Analyst challenges all work before it reaches the user
5. Every user decision is captured as structured project knowledge

See `/agency/CONSTITUTION.md` for the full 16 operating orders.
