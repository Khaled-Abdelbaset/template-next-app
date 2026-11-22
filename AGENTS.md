# Agent instructions — Next.js

## Commands

- Install: `npm ci`
- Dev: `npm run dev`
- Typecheck: `npx tsc --noEmit`
- Build: `npm run build`

## Repository

- **Stack:** Next.js (App Router), TypeScript
- **Default branch:** `main` (protected; PRs only)

## Git & PR

- **Handbook:** [GIT_WORKFLOW.md](https://github.com/Khaled-Abdelbaset/engineering-standards/blob/main/docs/GIT_WORKFLOW.md)
- **Commit email:** [GIT_IDENTITY.md](https://github.com/Khaled-Abdelbaset/engineering-standards/blob/main/docs/GIT_IDENTITY.md)
- Branch from `main`: `feat/`, `fix/`, `chore/`, `docs/`
- **Conventional Commits:** `feat(frontend): …`, `fix(ui): …`, `chore(ci): …`
- PR body: Summary, Test plan, Cross-repo links if API contract changes
- Squash merge after CI **build** is green
- Do **not** `git commit` or `git push` unless the user explicitly asks
- Never commit `.env`, secrets, `.next/`, or `tsconfig.tsbuildinfo`

## Cross-repo

- Backend API breaking changes: merge/deploy backend **before** dependent frontend PRs

## Large initiatives

- One branch and one PR per phase; tracker in `docs/*-TRACKER.md` when present
- See [GIT_WORKFLOW §11](https://github.com/Khaled-Abdelbaset/engineering-standards/blob/main/docs/GIT_WORKFLOW.md#11-large-initiatives-multi-phase-work)

## Tool-specific mirrors

| Tool | Path |
|------|------|
| Cursor | `.cursor/rules/git-workflow.mdc` (always apply) + stack rule |
| Claude Code | `CLAUDE.md` imports this file; `.claude/rules/git-workflow.md` |

**Agent layering:** [AGENT_INSTRUCTIONS.md](https://github.com/Khaled-Abdelbaset/engineering-standards/blob/main/docs/AGENT_INSTRUCTIONS.md)