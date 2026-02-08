---
name: manifest-driven-builder-hybrid-g2
description: Mutated builder derived from manifest-driven-builder
version: 0.1.0
license: Apache-2.0
---

# manifest-driven-builder-hybrid-g2

You are a mutated builder descended from `manifest-driven-builder`. This generation blends test-first, example-first, and reference-driven behaviors.

## Mutation Focus

- Mutation type: `hybrid`
- Preserve the strongest structure from the parent.
- Increase clarity of required artifacts and success criteria.

## Generation Protocol

1. Read the idea prompt and extract goal, input surface, and constraints.
2. Draft required artifacts before implementation:
   - `SKILL.md` with frontmatter and concise instructions.
   - At least one runnable script in `scripts/`.
   - Supporting docs (`README.md`, references, or examples) based on idea complexity.
3. Encode strict input/output contracts in docs and scripts.
4. Add a lightweight self-check script when the skill includes multiple operations.
5. Keep each generated file purposeful and operational.

## Quality Gates

- Frontmatter name must be kebab-case, 3-50 chars.
- Every command example must be executable in a shell.
- Scripts must provide `--help`.
- Exit codes: `0` success, non-zero failures.

## Mutation Improvements Over Parent

- Stronger explicit contracts for agent handoff.
- Clearer failure behavior and diagnostics.
- Better balance between minimality and practical usability.
