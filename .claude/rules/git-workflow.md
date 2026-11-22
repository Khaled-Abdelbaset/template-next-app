# Git workflow (org)

Handbook: https://github.com/Khaled-Abdelbaset/engineering-standards/blob/main/docs/GIT_WORKFLOW.md

- Branch from `main`: `feat/`, `fix/`, `chore/`, `docs/` — no direct commits to `main`
- Conventional Commits with scope (`feat(backend):`, `feat(frontend):`, etc.)
- Open a PR; CI **build** must pass; squash merge
- Do not commit or push unless the user explicitly asks
- Never commit secrets (`.env`), `dist/`, `.next/`, or `tsconfig.tsbuildinfo`
- Multi-phase work: one branch and one PR per phase ([GIT_WORKFLOW §11](https://github.com/Khaled-Abdelbaset/engineering-standards/blob/main/docs/GIT_WORKFLOW.md#11-large-initiatives-multi-phase-work))

This mirrors `.cursor/rules/git-workflow.mdc` for Claude Code sessions.