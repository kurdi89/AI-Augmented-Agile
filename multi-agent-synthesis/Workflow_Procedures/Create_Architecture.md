# Workflow Procedure: Create Architecture

**Trigger:** `PRD.md` is approved by a human.

## 1. Activate Agents

The Central Orchestrator activates the following agents:
- `Solution Architect Agent`
- `Technical Designer Agent`

## 2. Execute Tasks

1.  The `Solution Architect Agent` reads the approved `PRD.md`.
2.  The `Solution Architect Agent` creates the high-level sections of the `TDD.md` based on the `Infrastructure_Architecture_Template.md`.
3.  The `Technical Designer Agent` reads the high-level `TDD.md`.
4.  The `Technical Designer Agent` populates the detailed design sections of the `TDD.md`, including component designs and API specifications.
5.  The `Solution Architect Agent` runs the `Architect_Checklist.md` to verify completeness.

## 3. Request Human Review

Once the `TDD.md` is complete and has passed the checklist, the Central Orchestrator flags it for human review and approval.
