# agent-workflow-template

A documentation template that helps coding agents stay focused, follow project constraints, understand the reasons behind technical decisions, and continue work across sessions.

## Getting Started

1. Copy this structure and replace the placeholders to match your project.
2. Fill in `AGENTS.md` with a short project overview and relevant reading paths.
3. Define the active milestone in `docs/roadmap.md` (only one at a time).
4. Establish project rules in `docs/guidelines.md` and record agreed technical decisions in `docs/architecture.md`.
5. At the end of each session, append a short entry to `CHANGELOG-agent.md`.

## Structure

```text
.
├── AGENTS.md              # Agent entry point and instruction index
├── CHANGELOG-agent.md     # Cross-session memory, append-only
└── docs/
    ├── roadmap.md         # Active milestone and completion criteria
    ├── guidelines.md      # Required rules, preferences, and prohibitions
    └── architecture.md    # Technical decisions and their rationale (ADRs)
```

## Usage Principles

- Read only the documents needed for the task; `AGENTS.md` directs the agent to the relevant documents.
- Direct user instructions determine task scope. For conflicting project rules, follow the precedence order in `AGENTS.md`; ask for clarification if a conflict cannot be resolved safely.
- Every roadmap criterion must be verifiable. Do not move to another milestone without user approval.
- Record new decisions as ADRs; do not erase the history of superseded decisions.
- Append changelog entries only at the end of a session, using the fixed three-item format.

This template does not assume a programming language, framework, or test command. Replace examples and placeholders so they fit your repository.
