# Workflow Procedure: Create Next Story Task

**Trigger:** `TDD.md` is approved by a human.

## 1. Activate Agents

The Central Orchestrator activates the following agents:
- `Product Owner Agent`
- `Scrum Master Agent`

## 2. Execute Tasks

1.  The `Product Owner Agent` reads the approved `TDD.md` and `PRD.md`.
2.  The `Product Owner Agent` decomposes the work into `Epics/` and `User_Stories/` using the appropriate templates.
3.  The `Product Owner Agent` prioritizes the backlog of user stories.
4.  The `Scrum Master Agent` initiates a new sprint and creates a `Sprint_Plan.md`.
5.  The `Scrum Master Agent` assigns the highest-priority user story to an available `Developer Agent`.

## 3. Initiate Development

The Central Orchestrator activates the assigned `Developer Agent`, `QA Agent`, and `DevOps Agent` to begin the implementation cycle for the assigned user story.
