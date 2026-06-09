# dotclaudemd — Claude Code workspace

Layered project instructions for this SaaS-style CLI codebase.

## Quick commands

```bash
npm run build
npm test
npm run lint
```

## Modular rules (imported)

@import ./claude/core-standards.md
@import ./claude/cli-conventions.md

## Path-specific rules

File-aware rules live in `.claude/rules/` and load automatically when editing matching paths.
