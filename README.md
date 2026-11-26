# agent-workflow-template

A reusable documentation system that keeps AI coding agents focused, constrained, and able to continue work across sessions.

## What This Template Provides

- `AGENTS.md`: the entry point and concise operational index.
- `docs/roadmap.md`: the active goal and verifiable completion criteria.
- `docs/guidelines.md`: mandatory, preferred, and prohibited project rules.
- `docs/architecture.md`: Architecture Decision Records (ADRs) for durable technical choices.
- `CHANGELOG-agent.md`: append-only, three-item context for the end of each session.

## Using the Template

1. Copy this repository as a starting point for the target project.
2. Replace the **Project Context** section in `AGENTS.md` with confirmed facts.
3. Keep only project-wide rules in `docs/guidelines.md`; remove all examples that do not apply.
4. Open one milestone in `docs/roadmap.md` and write acceptance criteria that can be verified.
5. Record only decisions that have actually been made in `docs/architecture.md`.
6. Append one entry to `CHANGELOG-agent.md` when a session ends.

## Documentation Rules

- The user’s direct instruction is the highest-priority source for each task.
- Project precedence is declared in `AGENTS.md`.
- Read only the documents necessary for the current task.
- Clearly distinguish verified facts, assumptions, proposed work, and unresolved questions.
- Never invent project architecture, dependencies, test results, users, or decisions.
- Do not use an example as a real requirement until the project owner confirms it.
- Keep the roadmap, guidelines, architecture, and changelog synchronized with their respective update rules.

## Repository Structure

```text
.
├── AGENTS.md
├── CHANGELOG-agent.md
├── docs/
│   ├── architecture.md
│   ├── guidelines.md
│   └── roadmap.md
└── README.md
```

## Example Versus Real Context

Because this repository is a template, it contains annotated examples rather than facts about a particular application. Before applying it to a real project, replace or remove them. In `docs/architecture.md`, for example, none of the sample decisions should be treated as accepted architecture until a real ADR is written and approved.

This template is documentation, not a substitute for source code, test output, package manifests, database schemas, or direct user requirements.
