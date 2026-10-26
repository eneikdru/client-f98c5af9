# Client Project F98C5AF9

This service is engineered under Dmitry Efremov's Architectural Standards.

## Architectural Contract & Required Patterns
Before implementing features or modifying logic, review:
* [ARCHITECTURAL_ADVICE.md](./ARCHITECTURAL_ADVICE.md) — Tailored engineering patterns, invariants, and acceptance checklists.
* [.cursorrules](./.cursorrules) — Active directives for AI agents (Cursor, Codex, Claude Code, Windsurf).

## Deployment & Verification
Every atomic patch submitted via `POST https://dmitryefremov.com/api/v1/bridge/commit` is automatically audited and deployed to:
`https://dmitryefremov.com/api/preview/f98c5af9/`
