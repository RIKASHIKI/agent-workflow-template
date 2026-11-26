# Project Guidelines

This document separates strict requirements, preferences, and prohibitions. Replace examples with confirmed project rules and remove anything that does not apply.

## MUST

A short list of verifiable, project-wide requirements. Until the target project supplies these rules, this section contains no approved requirements.

- [Replace this line with a confirmed requirement that can be checked.]
- [Example: Keep secrets out of source control.]
- [Example: Route external integrations through the project's adapter or service layer.]

Keep the list no longer than approximately 10 items. Each item should identify a behavior or an automated/manual check that can prove compliance.

## SHOULD

Preferences that may be overridden when a contributor explains why the alternative is more appropriate.

- [Example: Prefer the smallest understandable change.]
- [Example: Add or update tests for behavior that could regress.]
- [Example: Keep functions and modules focused on one responsibility.]

## MUST NOT

Actions that require explicit approval or are prohibited in every project context.

- [Example: Do not commit credentials or private keys.]
- [Example: Do not edit applied database migrations.]
- [Example: Do not install dependencies without approval unless a task explicitly requires them.]
- [Example: Do not perform destructive operations unless the user has approved the exact action.]

## Handling Uncertainty

- Treat all bracketed examples as suggestions, not facts.
- Treat an unconfirmed rule as unresolved rather than inferred.
- Ask for clarification before choosing between conflicting mandatory rules.
- Do not weaken a security, privacy, data-integrity, or legal requirement merely for convenience.
- Add a new rule only when it is proven, agreed upon, or explicitly requested.

## Handling Conflicts

Use the precedence declared in `AGENTS.md`. Direct user instructions determine task scope, while this file supplies project-specific mandatory constraints. A conflict that affects security or data integrity must be discussed before implementation.
