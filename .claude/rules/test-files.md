---
globs: **/*.test.ts
---

# Test file conventions

When editing `*.test.ts` files:

- Mirror `src/` layout under `tests/`
- Use fixtures from `tests/fixtures/` — do not inline large template trees
- Prefer descriptive `describe` / `it` blocks that name the command or linter rule under test
- Assert on structured output (JSON, exit codes) rather than full console snapshots
