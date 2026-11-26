# Instructions for Agents

## Project Context

This repository is a template for organizing long-running work on AI-assisted software projects. It does not describe a production application. Confirm all project-specific details before using this structure as instructions for a particular repository.

This template may be adapted to any programming language or framework. Do not assume a technology stack, build system, deployment target, database, or test command that is not explicitly supplied.

## Precedence

Direct instructions from the user take precedence over every project document.

For project rules that conflict, use this static order:

1. `docs/guidelines.md`
2. `docs/architecture.md`
3. `docs/roadmap.md`

If the documents are ambiguous or a proposed change could damage data, violate security boundaries, or change approved scope, stop and ask the user for clarification. Do not silently choose a conflicting interpretation.

## Reading Guide

| When | Read |
|---|---|
| At the start of every task | This file |
| At the start of a new task or session | `docs/roadmap.md` |
| Before modifying code | `docs/guidelines.md` |
| Before changing data structures, APIs, interfaces, or technical dependencies | `docs/architecture.md` |
| When continuing from an earlier session | Latest entry in `CHANGELOG-agent.md` |
| Before creating or deleting a project file | Relevant project files and the applicable guidance below |
| At the end of a session | Append a three-item entry to `CHANGELOG-agent.md` |

## Working Method

- Work only on the explicitly active milestone. If no milestone is active, ask before beginning implementation.
- Use only information available in the repository or supplied by the user. Label assumptions explicitly.
- Never claim that tests, builds, migrations, reviews, or deployments passed unless they were actually run and produced evidence.
- Preserve existing behavior unless a change is requested or required by an approved milestone.
- Make the smallest reviewable change that satisfies the task.
- Report completed work, verification performed, unresolved questions, and recommended next actions.
- Do not add dependencies, migrations, secrets, external services, or destructive operations unless explicitly approved or strictly necessary and confirmed.

## Evidence and Verification

Before marking work complete:

1. Identify a concrete completion check.
2. Run the narrowest relevant check, or explain why it is unavailable.
3. Inspect the resulting diff.
4. Record the exact command or manual evidence used when available.

If a check cannot be run, report it as not run; never substitute a claim of success.
