---
globs: **/src/**/*.ts
---

# TypeScript source conventions

When editing files under `src/`:

- Keep imports ESM with explicit `.js` extensions
- Inject filesystem and prompt dependencies — avoid hard-coded `fs` in core logic
- Export types from `src/types.ts` when shared across commands
