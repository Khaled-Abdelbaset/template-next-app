# Contributing

**Full handbook:** [engineering-standards → GIT_WORKFLOW.md](https://github.com/Khaled-Abdelbaset/engineering-standards/blob/main/docs/GIT_WORKFLOW.md)

## Quick flow

1. `git checkout main && git pull`
2. `git checkout -b feat/short-name`
3. Code + local build (see README)
4. `git push -u origin HEAD` → open PR to `main`
5. Wait for **CI** → squash merge

## What runs on GitHub

| Workflow | When |
|----------|------|
| **CI** | Every PR and push to `main` (reusable build from `engineering-standards`) |
| **Discord Notify** | Push/merge to `main`; CI failure on `main` (if `DISCORD_WEBHOOK_URL` is set) |

## Git author email

Set the email tied to **Khaled-Abdelbaset** on GitHub — see [GIT_IDENTITY.md](https://github.com/Khaled-Abdelbaset/engineering-standards/blob/main/docs/GIT_IDENTITY.md).