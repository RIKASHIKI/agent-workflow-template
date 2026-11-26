# Project Guidelines

Replace bracketed examples with rules agreed upon for this project. Remove rules that are not relevant. If a rule has not been established, mark it as not yet decided rather than treating an example as a fact.

## MUST

Strict rules that apply to every change and can be verified. Keep this list short (about 10 rules or fewer).

1. [Example: Route all database access through a repository layer, if the project uses one.]
2. [Example: Never store secrets or credentials in the repository.]
3. [Add another project rule that can be verified.]

## SHOULD

Preferences that may be overridden with a brief explanation in the change or work summary.

- [Example: Prefer small, easily tested functions where they fit the project design.]
- [Add another project preference.]

## MUST NOT

Actions that require explicit user approval.

- [Example: Do not change or delete migrations that have already been applied.]
- [Example: Do not add dependencies without requesting approval.]
- [Add project-specific constraints; ensure they do not conflict with newer user instructions.]

## Handling Conflicts

Follow the precedence order defined in `AGENTS.md`. Direct user instructions determine the request's scope, but changes that violate security boundaries or risk damaging data must be clarified before proceeding. Do not silently choose an interpretation when mandatory rules conflict.
