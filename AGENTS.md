# Instructions for Agents

## Project Overview

> Replace this section with 2–3 sentences describing what this project builds, who it is for, and which stack or environment it uses. Do not include assumptions that have not been confirmed.

## Precedence

Direct instructions from the user determine task scope and take precedence over project documentation. For conflicting project rules, use this order: `docs/guidelines.md` > `docs/architecture.md` > `docs/roadmap.md`. If a conflict remains ambiguous or affects security or data, stop and ask for clarification.

## Reading Guide

| When | Read |
|---|---|
| At the start of a task | This document |
| When selecting or confirming active work | `docs/roadmap.md` |
| Before changing code | `docs/guidelines.md` |
| When changing data structures, APIs, or technical decisions | `docs/architecture.md` |
| When continuing work from a previous session | Latest entry in `CHANGELOG-agent.md` |
| When ending a session | Append three items to `CHANGELOG-agent.md` |

## Working Method

- Work only on the active milestone unless the user explicitly requests otherwise.
- Ensure completion criteria are verifiable; run available checks and report their results.
- Do not modify unrelated documentation. Update the roadmap only when a milestone is opened or closed, record an ADR when a decision is made, and append to the changelog at the end of a session.
- Never invent decisions, statuses, test results, or placeholder content. Ask if important information is unavailable.
