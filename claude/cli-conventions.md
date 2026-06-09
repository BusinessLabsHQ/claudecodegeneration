# CLI & command conventions

- Commander subcommands live in `src/commands/` — one file per command
- User-facing output goes through `src/utils/ui.ts` and `src/utils/logger.ts`
- Errors use typed helpers from `src/utils/errors.ts`
- New commands must register in `src/cli.ts` and include vitest coverage under `tests/`
