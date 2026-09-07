# Agency Workflow

## Operating Model

```
User → Agency Director → Specialist Team → Internal Challenge → Agency Director → User
```

## Standard Project Flow

### 1. Project Opens (Day)
User brings a project or task to the Agency Director.

### 2. Director Sets Up (Day)
- Creates `/projects/[client]/[project]/` in GitHub
- Creates all six project files from the template
- Briefs all four specialist agents with the project brief
- Collects each agent's initial assessment

### 3. Evening Report (Before 00:00 Helsinki)
Director sends a concrete plan: which agent does what tonight, what deliverables to expect in the morning.

### 4. Night Cycle (00:00–06:00 Helsinki)
All agents execute their assigned tasks.

Workflow within the night cycle:
```
1. Director briefs agents with project context + GitHub knowledge files
2. Specialists (Strategist, Creative, Copywriter) produce their work
3. Analyst reviews and challenges with specific critique
4. Director routes critique back to relevant agents
5. Agents revise
6. Director compiles final outputs
7. Director updates JOURNAL.md and STATUS.md
```

### 5. Morning Report (Morning)
Director sends: Completed / Key findings / Decisions required / Recommended next step.

### 6. User Review (Day)
User reviews, approves, rejects, or modifies work. All decisions are captured in DECISIONS.md.

### 7. Repeat
Next evening report is based on approvals received during the day.

---

## Approval Stages

| Stage | Meaning |
|-------|---------|
| DRAFT | Agent has produced something |
| INTERNAL REVIEW | Analyst is challenging it |
| USER REVIEW | Waiting for user decision |
| APPROVED | User has confirmed |
| PRODUCTION | Being executed at full scale |
| COMPLETED | Done and documented |

**Critical:** No deliverable moves from INTERNAL REVIEW to USER REVIEW without the Analyst challenge loop completing.

---

## Decision Capture

Every meaningful user decision is captured immediately:

```
## DECISION-[NNN]
Date: YYYY-MM-DD
Decision: [what was decided]
Alternatives: [what was rejected]
Reason: [why]
Impact: [which agents / work is affected]
Status: APPROVED
```

---

## Knowledge Loading

When an agent begins work on any project, the Director ensures they load:
1. Their own ROLE.md, SKILLS.md, and PLAYBOOKS.md from `/agents/[agent]/`
2. The project's BRIEF.md, STATUS.md, and DECISIONS.md
3. Any client-specific brand documentation

Agents do not work from memory alone.
